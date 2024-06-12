# Weather_Recognition_ResNet34
Weather recognition is a classification computer vision project that uses ResNet34 backbone to forecast the weather

Takes 30-40 minutes when trained in Google Colaboratory

# Dataset 
Weather dataset (link to download in the code file) which has 6862 pictures (samples) for 11 kinds of weather (dew, fogsmog, frost, glaze, hail, lightning, rain, rainbow, rime, sandstorm, snow) 

# Progamming language
Python

# Download model checkpoint
```
!gdown --id 1AJDd2GWpVC9PzPPza6m6DE3pEPGViuM_
```

# Model performance 
Model performance with ResNet34 and 50 epochs:

![image](https://github.com/Vu0401/Weather_Recognition_ResNet34/assets/93986576/20143caa-6742-4503-b8ae-8ffdfd3abbf1)
![image](https://github.com/Vu0401/Weather_Recognition_ResNet34/assets/93986576/67a95ea0-ba99-4691-8bae-77a093de4c80)

# Inference
```python
search(r'dataset\rainbow\107.jpg')
```
![image](https://github.com/Vu0401/Weather_Recognition_ResNet34/assets/93986576/9a36c337-4bf3-464a-93da-31673eb9fb81)

