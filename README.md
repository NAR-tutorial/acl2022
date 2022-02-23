# Non-Autoregressive Sequence Generation
Tutorial @ [ACL 2022](https://www.2022.aclweb.org/), May 22-27, 2022


## Speakers
[Jiatao Gu](https://jiataogu.me/), Facebook AI Research, <jgu@fb.com> <br>
[Xu Tan](https://www.microsoft.com/en-us/research/people/xuta/), Microsoft Research Asia, <xuta@microsoft.com> 



## Abstract
Non-autoregressive sequence generation (NAR) attempts to generate the entire or partial output sequences in parallel to speed up the generation process and avoid potential issues (e.g., label bias, exposure bias) in autoregressive generation. While it has received much research attention and has been applied in many sequence generation tasks in natural language and speech, naive NAR models still face many challenges to close the performance gap between state-of-the-art autoregressive models because of a lack of modeling power. In this tutorial, we will provide a thorough introduction and review of non-autoregressive sequence generation, in four sections: 1) Background, which covers the motivation of NAR generation, the problem definition, the evaluation protocol, and the comparison with standard autoregressive generation approaches. 2) Method, which includes different aspects: model architecture, objective function, training data, learning paradigm, and additional inference tricks. 3) Application, which covers different tasks in text and speech generation, and some advanced topics in applications. 4) Conclusion, in which we describe several research challenges and discuss the potential future research directions. We hope this tutorial can serve both academic researchers and industry practitioners working on non-autoregressive sequence generation. 


## Outline

    PART 1  Introduction (~ 20 minutes) 
      1.1 Problem definition 
      1.2 Evaluation protocol 
      1.3 Multi-modality problem 
      
    PART 2  Methods  (~ 90 minutes) 
      2.1 Model architectures 
          2.1.1  Fully NAR models 
          2.1.2  Iteration-based NAR models 
          2.1.3  Partially NAR models 
          2.1.4  Locally AR models 
          2.1.5  NAR models with latent variables 
      2.2 Objective functions 
          2.2.1  Loss with latent variables 
          2.2.2  Loss beyond token-level 
      2.3 Training data 
      2.4 Learning paradigms 
          2.4.1  Curriculum learning 
          2.4.2  Adversarial training 
          2.4.3  Self-supervised pre-training 
      2.5 Inference methods and tricks 
      
    PART 3  Applications  (~ 50 minutes) 
      3.1 Text generation 
          3.1.1  Neural machine translation 
          3.1.2  Text summarization 
          3.1.3  Text error correction 
          3.1.4  Automatic speech recognition 
      3.2 Speech generation 
          3.2.1  Text to speech 
          3.2.2  Voice conversion 
      3.3 Advanced topics in applications 
          3.3.1   Advanced length prediction 
          3.3.2  Alignment (duration vs attention)
          3.3.3  Target token dependency
          3.3.4  Relationship with streaming
          
    PART 4  Open problems, future directions, Q\&A  (~ 20 minutes)
    
## Materials
[Slides (To be released)](TBD)<br>


