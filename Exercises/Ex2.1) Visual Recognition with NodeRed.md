#Ex2.1) Visual Recognition with NodeRed

### Overview
In this part of the exercise you will build your first flow in NodeRed. You will use the camera of the RaspberryPi to take a picture and the Visual Recognition service to analyze.  
In the picture below you find

*Steps*
1. User takes a picture over User Interface (UI)
2. RaspberryPi trigers the camera and the picture is saved locally until the next picture is taken.
3. After preprocessing the picture is displayed in the UI
4. User triggers to analyze picture
5. The picture is sent to the IBM Cloud, analyzed by Visual Recognition and the results are sent back to the Raspberry
6. The results of the picture are preprocessed and displayed in the UI

![alt text](https://github.com/you-R-I/workshops/blob/master/images/Ex1-Description.png "Overview Ex2.1")
