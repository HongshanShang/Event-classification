# Event-classification
This research is dedicated to providing comprehensive model building guidance in the field of event analysis for those with limited computing calculation ability. 

The model has three outstanding advantages.
- reduces the amount of computing without sacrificing much accuracy. By doing so, devices with limited computing power could drastically reduce their computing costs.
- Fast and simple to build, which is very convenient for users with limited time and reduces time costs.
- Easy to adjust. Users only need to adjust individual parameters or adjust individual modules to achieve the desired function.

This study designed four types of models. 
- Single image data type classification model
- Single sound data type classification model
- Vitual and audio multimodal model 
- Vitual and audio multimodal model with attention mechanisms

## Dataset 
AVE Dataset [[1]](https://sites.google.com/view/audiovisualresearch)
## Features
Audio and visual feature can be downloaded [here](https://drive.google.com/file/d/1bIiWakMw4neXDYPO_9H_gGN_UcikWa7I/view?usp=sharing). Audio feature are extracted with a VGGish network [2] and visual feature are extracted with DenseNet [3]

Scripts for generating audio and visual features are in feature_extractor folder (Feel free to modify and use it to process your audio-visual data)
