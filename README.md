# drown_detector_alpha
alpha version implemented with faster rcnn v2 incepction architecture
 for installation:
 
 basic requirments:
 
1) install python 3.6.8 on your pc
2) activate virtual env provided in the code before installation
 
virtual env activation:
1)open command line in suitable directory as follow : "....Test_Faster\Scripts\activate
2) you will see you in environment called :"Test_Faster"
3) now go to directory: Test_Faster\object_detection
4) run requierments installation by : "pip install -r req requirements.txt"
5) after it will finish your enviroment ready


** important : without GPU support the latency is much more slower in 4 times.
for improve runing do it with GPU nvidia with cuda libary.
it will work with cuda installation v10.0
and external libaries cudnn v7.4


***************************************************************************
to run the offline video of detections:

from directory : ....Test_Faster\object_detection

run "python video_testing.py [direct directory for video file]"

all videos are in : "Test_Faster\object_detection\testing\videos"



*************************************************************************
to demostrate the ability of the algorithm and system to support real-time detection with webcam:
from directory : ....Test_Faster\object_detection

run "python CAM_testing.py 0"


it will be slow without GPU support be notice

