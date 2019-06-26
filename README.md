# FRAS
Face Recognition attendance system

## DEMO : https://www.youtube.com/watch?v=Gmyu9Ehegsc
[![Little red ridning hood](https://img.youtube.com/vi/Gmyu9Ehegsc/0.jpg)](https://www.youtube.com/watch?v=Gmyu9Ehegsc "FRAS Youtube Video - Click to Watch!")
<p><span style="font-size: 15pt;">Setup</span></p>
<p>1.Install anaconda or python (anaconda is recommended )</p>
<p>&nbsp; &nbsp;<a href="https://www.anaconda.com/distribution/">Download Anaconda</a></p>
<p>&nbsp; &nbsp;<a href="https://www.python.org/">Download Python 3.6</a></p>
<p>2. Install following dependencies</p>
<ul>
<li>numpy - 1.11.3 (remommended version)</li>
<li>scipy&nbsp; - 1.2.1 (recommended version)&nbsp; &nbsp;&nbsp;</li>
<li>pandas&nbsp; - 0.24.1 ( use pip to install pandas)</li>
<li>pillow</li>
<li>matplotlib</li>
<li>face_recognition</li>
<li>face_recognition_models</li>
<li>dlib 19.9 (recommended version)</li>
</ul>
<p>&nbsp; If you are using Anaconda-python run the follow commands to install dependencies</p>
<pre><code>  conda create -n py36 python=3.6
  activate py36
  conda config --add channels conda-forge
  conda install numpy
  conda install scipy 
  conda install dlib
  pip install --no-dependencies face_recognition
  conda install -c akode face_recognition_models
  pip install pandas<br />  pip install matplotlib
  pip install Pillow
  
  pip install pyttsx3
  pip install pypiwin32
  
  </code></pre>
  
<p><span style="font-size: 15pt;">Running&nbsp;</span></p>
<p>&nbsp; &nbsp;Just open terminal and switch to environment(py36) in anaconda</p>
<p>&nbsp; &nbsp;run this&nbsp; <strong>python firstpage.py&nbsp;</strong></p>
<p>&nbsp;</p>
