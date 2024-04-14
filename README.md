# Age Detection of Insulators   

<h2>Objective :</h2>
<p>To Determine age of insulators using images </p>

<h2>About the Project :</h2>
<p>In this  Project, I had used Deep Learning to accurately identify the  age of insulators from image of insulators  . I used the models trained by <a href="https://talhassner.github.io/home/projects/Adience/Adience-data.html">Tal Hassner and Gil Levi</a>. The predicted age  may be  one of the following ranges- 0 to 50 years . It is very difficult to accurately guess an exact age from a single image because of factors like picture clarity ,pollution and dust . And so, I made this a classification problem instead of making it one of regression.</p>

<h2>Dataset :</h2>
<p>For this project, I had used the Adience dataset; the dataset is available in the public domain and you can find it <a href="https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification">here</a>. This dataset serves as a benchmark for insulator photos and is inclusive of various real-world imaging conditions like pollution and dust and humidity. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 13,000 photos ofLabels :5373 having the Val,Train,Set  ranges (as mentioned above) and is about 1GB in size. The models I used had been trained on this dataset.</p>

<h2>Additional Python Libraries Required :</h2>
<ul>
  <li>OpenCV</li>
  
       pip install opencv-python
</ul>
<ul>
 <li>argparse</li>
  
       pip install argparse
</ul>

<h2>The contents of this Project :</h2>
<ul>
  <li>opencv_age_detector.pbtxt</li>
  <li>opencv_age_detector_uint8.pb</li>
  <li>age_deploy.prototxt</li>
  <li>age_net.caffemodel</li>
  <li>insulator_deploy.prototxt</li>
  <li>insulator_net.caffemodel</li>
  <li>a few pictures to try the project on</li>
  <li>detect.py</li>
 </ul>
 <p>For age  detection, we have a .pb file- this is a protobuf file (protocol buffer); it holds the graph definition and the trained weights of the model. We can use this to run the trained model. And while a .pb file holds the protobuf in binary format, one with the .pbtxt extension holds it in text format. These are TensorFlow files. For age , the .prototxt files describe the network configuration and the .caffemodel file defines the internal states of the parameters of the layers.</p>
 
 <h2>Usage :</h2>
 <ul>
  <li>Download my Repository</li>
  <li>Open your Command Prompt or Terminal and change directory to the folder where all the files are present.</li>
  <li><b>Detecting  Age of insulator in Image</b> Use Command :</li>
  
      python detect.py --image <image_name>
</ul>
  <p><b>Note: </b>The Image should be present in same folder where all the files are present</p> 
<ul>
  <li><b>Detecting  Age of insulator through image</b> Use Command :</li>
  
      python detect.py
</ul>
<ul>
  <li>Press <b>Ctrl + C</b> to stop the program execution.</li>
</ul>

# Working:


<h2>Examples :</h2>
<p><b>NOTE:- I downloaded the images from Google,if you have any query or problem i can remove them, i just used it for future purpose.</b></p>

   
   
  
    
              
