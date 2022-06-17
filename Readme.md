# Introduction

In this notebook, a model primarily similar to U-Net is trained to segment images of pets. The performance of the model is analyzed using intersection over union and per pixel accuracy. The data used is the Oxford Pet Dataset, available [here](https://www.robots.ox.ac.uk/~vgg/data/pets/).

# Note/Possible Future Analysis
Ideally, to pick apart the discrepancy between the loss and metrics, I would look at the output of several epochs, in order to gather evidence for my explanations. Due to time (and memory) constraints, I have put this off to the future.