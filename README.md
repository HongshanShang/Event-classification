# Event-classification
This research is dedicated to providing comprehensive model building guidance in the field of event analysis for those with limited computing calculation ability. 

The model has three outstanding advantages.
- reduces the amount of computing without sacrificing much accuracy. By doing so, devices with limited computing power could drastically reduce their computing costs.
- Fast and simple to build, which is very convenient for users with limited time and reduces time costs.
- Easy to adjust. Users only need to adjust individual parameters or adjust individual modules to achieve the desired function.

This study designed four types of models. 
- Single visual data type classification model
- Single audio data type classification model
- Vitual and audio multimodal model 
- Vitual and audio multimodal model with attention mechanisms

## Dataset 
AVE Dataset [[1]](https://sites.google.com/view/audiovisualresearch)
## Tools 
* Language： Python
* IDE： Pycharm
* library and package:
*   Tensorflow
*   Keras
*   scipy.io
*   pillow
*   resampy
*   ffmpeg
*   pickle
  
## Single visual data type classification model
This model aims to identify and analyze a single image, identify the objects in the image, analyze the events that occurred in the image, and label the image.
- Vmodel.ipynb
## Single audio data type classification model
This model is dedicated to the recognition and analysis of a single sound environment. It identifies various sounds and events in the audio and adds corresponding labels to these audios. 
- Vmodel.ipynb
## Visual and audio multimodal model
This model aims to simultaneously recognize images and sounds in complex environments, analyze complex scenes, and improve the adaptability of the model in complex environments through the complementarity between image and sound features.
- Vmodel.ipynb
## Visual and audio multimodal model with attention mechanisms
Using Attention Mechanisms to Focus on the Importance of Different Modal Features. In handling multimodal data, this study introduces attention mechanisms to dynamically focus on the importance of features across different modalities, further enhancing model performance. 
- Multimodel.ipynb
