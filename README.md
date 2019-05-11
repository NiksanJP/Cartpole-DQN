# Cartpole-DQN
This is a solution for the OPEN AI gym project cart pole using Deep Q Learning.

# Concept
First we use normal Q Learning to record the past expierence. Then using random actions we train the Deep learning model made using 
Tensorflow and Keras. We took in 4 items in the model and gave out one command that is zero for left and one for right. 

After build and compiling the model we predict the output. But it will make mistakes will such small information of the environment 
so we use REINFOCEMENT LEARNING meaning we correct its mistake while running the program.

We target a new value for each target meaning for every NEW reward we update the eward to something higher. So even if we get the same
data or state and we predict something correct, we update the record for that to be more correct than the record before.

# Use of save weights
I am not using save weights or load weights is because it is showing an error as it is a Tensorflow alpha pre release meaning that it
contains a lot of errors and warnings.

# Sources
This website is great USE IT!
https://keon.io/deep-q-learning/
