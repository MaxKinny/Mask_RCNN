# Training on Your Own Dataset Step by Step
Labeling Tool: Best to use [VIA 1.0.6](http://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.6.html).
## Introduction: 
I want to divide a crane into different parts. There are 2 ways to divide it.
**First way:**
Class Names = ['connection', 'claw']

In this case, 'claw' class has 2 instances, 'connection' has 1.
**Second way:**
Class Names = ['fixedPart', 'moveablePart']
To do that, I have to label 2 datasets and trained 2 maskRCNN models correspondingly.



## Step by step label my crane dataset via VIA



## Training
1. Train model for first way: 
cd <repo_root_path>/samples/ballon
