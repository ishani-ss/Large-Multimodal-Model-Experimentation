# LMM Preliminary Thoughts
This summary is based off the [following blog by TripleSee](https://github.com/Triplesee/Large-Multimodal-Model/blob/main/documents/LMM%20Technical%20Report.md). 

<br/>

## BUSINESS QUESTION:
To explore the “art-of-the-possible”. More specifically, to explore if and how LMMs can make the document understanding solution more effective, more efficient and more scalable. 

<br/>


## CURRENT DU PIPELINE:
- The Document Understanding (DU) pipeline is very complex and has multiple steps, with more than 10 machine learning models comprising the pipeline. This complexity makes it very difficult to scale. 
- The performance of models in the current DU pipeline needs improvement. Substantial effort will be required to obtain the training data, build and validate multiple models in the pipeline. 
- The DU Team has put a lot of effort to improve the efficiency of the DU pipeline, including: 
    1) Trying faster models;
    2) Parallel computing;
    3) Optimising post-processing;
    4) Having new hardware and a new platform.

  These have significantly improved the throughput of the DU pipeline. 

<br/>


## IMPROVEMENTS TO DU PIPELINE:
- Using one LMM can replace multiple machine learning models in the pipeline, simplifying the DU pipeline.
- Pre-trained LMMs (with large language model backbones) have the potential to handle general scenarios without retraining the models. 
- In addition to the optimisations to the DU pipeline that have taken place, want to explore whether LMMs can increase the throughput, particularly taking advantage of the versatility of LMMs to give the desired result in one step rather than multiple steps. 

<br/>


## LMM RESEARCH
Preliminary research on LMMs focuses on text content generation grounded in text prompts and image/video/audio.

<br/>


## DOCUMENT UNDERSTANDING
Document understanding involves the process of automated understanding, classifying and extracting information from either digital documents or scanned documents. 
The diversity of layouts and formats, low-quality scanned document images and the complexity of the template structure make document understanding challenging. 

<br/>


## IDEAS FOR FURTHER WORK:
- Test HuggingFace LMMs that have a small number of parameters for computational times and performance.
- Understanding the benefits and trade-offs between token-level and feature-level fusion in learnable connectors among LMMs.


<br/>
