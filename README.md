# weeds-TFLite
TFLite Object Detection

Basic training of a TFlite Efficient-det object detection model for usage with Raspberry PI4.  
The database is part of : "Sistema para identificação de plantas invasoras em lavouras com detectores de objetos aplicados a imagens e vídeos" (Carboni, D.; 2021)  
Published in:  
https://lume.ufrgs.br/handle/10183/222610  
  
  
# TFLite Training File 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/carboni123/weeds-tflite/blob/main/TFlite_trainweeds.ipynb)

# TFLite Load Trained Model
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/carboni123/weeds-tflite/blob/main/weeds_TFLite_loadfromexportedmodel.ipynb)

# TFLite script for Raspberry Pi4
Run tflite_detect_script.py  
Example: python3 tflite_detect_script.py --model weeds.tflite --image img_1597293167.46.png  
It''ll generate a detection_result.png file in the same folder.  