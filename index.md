# DSC 180A Methodology Assignment 4

**Name:** Alexander Takamoto  
**Email:** atakamoto@ucsd.edu  
**Section:** Efficient AI: Algorithms and Systems for Foundation Models (D38)  
**Mentor:** Zhijian Liu

## Quarter 2 Project Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me has been efficient image generation and mainly how we can speed up diffusion models without sacrificing too much image quality. I found Taylor forecasting especially interesting because instead of running the neural network at every step we can estimate some of its outputs using previous steps and it seems to keep image quality good so far.

**2. Describe a potential investigation you would like to pursue for your Q2 Project.**

I would like to look into how different methods of accelerating image generation compare in terms of speed, memory usage, and image quality. Specifically I want to explore whether combining Taylor forecasting with other optimization techniques could improve generation efficiency. I would also be interested in testing how well these methods work on smaller models that can run on lower end or more cheap hardware.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change I would make is to focus more on systematically evaluating different methods under the same conditions. Since our project involves comparing acceleration techniques its hard to always be able to use consistent models, prompts, and evaluation metrics. I would also like to spend more time understanding why certain methods perform better at different sampling steps rather than just comparing their overall runtimes.
