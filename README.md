<h1 align="center">Mask-Detection-Security</h1>

**“A Deep Learning Based Model For Detecting Mask Over Face In Public Places To Curtail Community Spread Of Covid-19 Is Presented”**

<div align= "center"><img src="https://github.com/yashshrivastavaa/Mask-Detection-Security/blob/main/LOGO/Logo.png" width="300" height="300"/>
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>  
  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

<h1 align="center">About Us</h1>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div align= "center"><img src="Project Documentation/Contributers/My Image.jpg" width="300" height="300"/>

</div> 


My name is **YASH SHRIVASTAVA**. At present I am pursuing my degree in *Bachelor of Technology in Electronics and Communication Engineering* from *Lakshmi Narain College of Technology Excellence, Bhopal*. My current CGPA is 9.3. I have done my schooling Panini Jnanpeeth School (M.P.). I have excellent problem-solving skills and ability to perform well in a team. Passionate of coding and contribute for the best with my skills for my service. Work to Achieve the Highest Goal. [See Profile](https://www.linkedin.com/in/yash-shrivastava-a116a81b3/) 


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div align= "center"><img src="Project Documentation/Contributers/My Image 3.jpg" width="300" height="300"/>
  
</div>
 
My name is **PUPUL BHATNAGAR**. At present I am pursuing my degree in *Bachelor of Technology in Electronics and Communication* from *Lakshmi Narain College of Technology Excellence, Bhopal*. My current CGPA is 8.42. I have done my schooling from Carmel Convent Senior Secondary School B.H.E.L. Bhopal (M.P.). I am able to handle multiple tasks on a daily basis and eager to learn new skills. Passionate to learn new skills and create by contribution towards the service. [See Profile](https://www.linkedin.com/in/pupul-bhatnagar-19b3821bb/)
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div align= "center"><img src="Project Documentation/Contributers/My Image 2.jpg" width="300" height="300"/>
  
</div>

My name is **SIMI KUSHWAHA**. At present I am pursuing my degree in *Bachelor of Technology in Electronics and Communication Engineering* from *Lakshmi Narain College of Technology Excellence, Bhopal*.  My current CGPA is 8.55. I have done my schooling from St. George Sr. Sec School Bhopal (M.P.). I’ve an optimistic mindset and do not shy away from hard work and dense deadlines and have lunacy towards the goals. [See Profile](https://www.linkedin.com/in/simi-kushwaha-742513176/)

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
```python
$ git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git
```

2. Change your directory to the cloned repo 
```python
$ cd Face-Mask-Detection
```
3. Create a Python virtual environment named 'test' and activate it
```python
$ virtualenv test
```
```python
$ source test/bin/activate
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```python
$ pip3 install -r requirements.txt
```

## 💡 Working

1. Open terminal. Go into the cloned project directory and type the following command:
```python
$ python3 train_mask_detector.py --dataset dataset
```

2. To detect face masks in an image type the following command: 
```python
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. To detect face masks in real-time video streams type the following command:
```python
$ python3 detect_mask_video.py 
```


##  📝  Feedback & Suggestion
[Click Here](https://forms.gle/7LxP9ffcgfKq2jDt8) for feedback & Suggestion

