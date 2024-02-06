After the 5 experiments with different variation in the hyperparameters, it's clear that in this case a learning rate of 0.005 and 256 neurons in the first layer yielded the most accurate model, as seen in experiement 2 and 4 with an accuracu score of 0.5755 and 0.5813 respectively. 

From the limited amount of research on the accuracy score, I have concluded that my model is a bit more precise than a lucky guess. I would have liked to go above at least 60% accuracy, to make sure model is not just guessing. I believe the issue here could be the simple structure and limited amount of layers. Yet, during my experimentation, I found that my model, as written now, would perform significantly worse (accuracy in the neighborhood of 15%) when i added either more hidden layers or made a more complex structure. Although i believe some more hyperparameter tuning could have helped with that.  

Results of the 5 experiments:
Experiment 1: Hidden Size 1=512, Hidden Size 2=64, Hidden Size 3=512, Learning Rate=0.02, Epoch=20
Test Accuracy: 0.5664
Experiment 2: Hidden Size 1=256, Hidden Size 2=64, Hidden Size 3=512, Learning Rate=0.005, Epoch=20
Test Accuracy: 0.5755
Experiment 3: Hidden Size 1=64, Hidden Size 2=256, Hidden Size 3=256, Learning Rate=0.02, Epoch=20
Test Accuracy: 0.5496
Experiment 4: Hidden Size 1=256, Hidden Size 2=512, Hidden Size 3=256, Learning Rate=0.005, Epoch=20
Test Accuracy: 0.5813
Experiment 5: Hidden Size 1=256, Hidden Size 2=128, Hidden Size 3=512, Learning Rate=0.02, Epoch=20
Test Accuracy: 0.5625