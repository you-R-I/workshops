# Ex2.1) Visual Recognition with NodeRed

### Overview
In this part of the exercise you will build your first flow in NodeRed. You will use the camera of the RaspberryPi to take a picture and the Visual Recognition service to analyze.  
In the picture below you find

**Steps**
1. User takes a picture over User Interface (UI)
2. RaspberryPi trigers the camera and the picture is saved locally until the next picture is taken.
3. After preprocessing the picture is displayed in the UI
4. User triggers to analyze picture
5. The picture is sent to the IBM Cloud, analyzed by Visual Recognition and the results are sent back to the Raspberry
6. The results of the picture are preprocessed and displayed in the UI

![alt text](https://github.com/you-R-I/workshops/blob/master/images/Ex1-Description.png "Overview Ex2.1")


### Part I: Create your NodeRed Flow

1. Open the terminal on your computer and connect to your RPi with the following SSH command:$ sudo ssh pi@<IP-Adress of the RPi>
2. In the Rpi-Terminal start Node-Red with the following command:
  $ node-red
3. Open Internetbrowser on your personal computer and open Node-Red:
http://<IP-Adresse des RPi>:1880/ 
4. Delete the existing flows
  Create a new flow by clicking on «+» and Name it «Ex1» Delete old flow by double click on the tab and press delete Click «Deploy» 
Install the additional Nodes (maybe they are already installed) «Manage Palatte» «Install» Search and install the following 3 nodes:	«node-red-dashboard»	«node-red-node-base64»	«node-red-contrib-camerapi»	«node-red-node-watson»
Restart NodeRed in the Rpi-Terminal «ctrl + C» node-red
Open again Node-Red on your Borwser: http://<IP-Adresse des RPi>:1880/ 
