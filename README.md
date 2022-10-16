# HybrUR
A Hybrid Physical-Neural Solution for Unsupervised Underwater Image Restoration


## Requirements
* Python 3
* Pytorch (with CUDA)
* Opencv-Python
* Pyyaml

## Project directory
* checkpoints -- the trained network parameters to reload the HybrUR model
* config -- deploy the testing parameters
* model -- methodology implementation
* results -- the storage path of generated images
* samples -- network input (underwater and in-air images)
* utils -- utility functions

## Usage
```Bash
cd `project root directory`
python test.py 
```
The generated results will be saved in the `results` folder
