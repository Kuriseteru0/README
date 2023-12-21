# Object Detection using Anaconda,Pythorch and Yolov5-master
# Installation Process
- Download the ZIP file of Yolov5-master in Github using this link (https://github.com/ultralytics/yolov5)
- Go to python.org to Download the latest version of python
- Go to Anaconda.com to download the app on your PC/Laptop
- Next is go to pytorch.org to install the pytorch change some fuctions since we are using Anaconda Prompt
  Python Build-Stable(l.13.1)
  Your OS - Windows "Take note: You can change depends on your OS wether it was LINUX or Mac"
  Package-Conda
  Compute Platform - CPU
-After changing it you will see a link that you will copy to install it on Anaconda 

# Once everything is set go to Anaconda prompt
-Paste the link that we get from pytorch 'conda install pytorch torchvision torchaudio cpuonly -c pytorch'
# After The Installation was Sucessfull go to Anaconda Prompt again
(base) C:\Users\Dateng>  
# This is the first thing you will see, take note 'Dateng' is the name of my windows 
-The next step is
(base) C:\Users\Dateng>python
# It will release the version of python we download
-The next step is Import our Pythorch
>> import pythorch # Take note make sure to install the pythorch, else it wouldn't Import
# Once it didn't error take a new tab of anaconda prompt to Install to our yolov5-master
STEP BY STEP PROCEDURE 
(base) C:\Users\Dateng> cd desktop
(base) C:\Users\Dateng>Desktop>cd yolov5-master
(base) C:\Users\Dateng>Desktop>yolov5-master> pip install -r requirements.txt #if this wont work Try installing Build tools for Visual Studio by going to 'Visualstudio.microsoft.com' 
