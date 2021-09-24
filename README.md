<h1 align="center">Mask-Detection-Security</h1>

“A Deep Learning Based Model For Detecting Mask Over Face In Public Places To Curtail Community Spread Of Covid-19 Is Presented”

<div align= "center"><img src="https://github.com/yashshrivastavaa/Mask-Detection-Security/blob/main/LOGO/Logo.png" width="200" height="200"/>
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>  
  
## :star: Features
Our face mask detector didn't use any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://github.com/yashshrivastavaa/Mask-Detection-Security/tree/main/dataset)

This dataset consists of __3339 images__ belonging to two classes:
*	__with_mask: 1755 images__
*	__without_mask: 1584 images__

## 🔑  Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/yashshrivastavaa/Mask-Detection-Security/blob/main/requirements.txt)

## 🚀  Installation
1. Clone the repo
```
$ git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git
```

2. Change your directory to the cloned repo 
```
$ cd Face-Mask-Detection
```

3. Create a Python virtual environment named 'test' and activate it
```
$ virtualenv test
```
```
$ source test/bin/activate
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

## 💡 Working

1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. To detect face masks in an image type the following command: 
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. To detect face masks in real-time video streams type the following command:
```
$ python3 detect_mask_video.py 
```

##  📝  Feedback & Suggestion
[Click Here](https://forms.gle/7LxP9ffcgfKq2jDt8) for feedback & Suggestion




