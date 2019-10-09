# Training on Your Own Dataset Step by Step
Labeling Tool: Best to use [VIA 1.0.6](http://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6.html).
## Introduction: 
I want to divide a crane into different parts. There are 2 ways to divide it. 

**First way:**

Class Names = ['connection', 'claw']

In this case, 'claw' class has 2 instances, 'connection' has 1.

**Second way:**

Class Names = ['fixedPart', 'moveablePart']

In this case, each part only have one instance.


## Step by step label my crane dataset via VIA
To do that, you may think I have to label 2 times to create 2 datasets and train 2 maskRCNN models respectively. Indeed, I have to train 2 models for above 2 kinds of division ways. However, due to the convenience of VIA, I can label these 2 datasets at once.


## Training
1. Train model for first way: 
```c
cd <repo_root_path>/samples/ballon
```
