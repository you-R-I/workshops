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

1. Connect to your RaspberryPi (either with ssh or working locally) and start NodeRed  
``` $ node-red```  
2. Open the editor your browser (either on your remote computer or on the RaspberryPi): http://{IP-Addresse of the RPi}:1880/
3. Create a new Flow
	- Create a new flow by clicking on «+» and Name it «Ex1»
	- Delete old flow (if no used anymore) by double click on the tab and press delete Click «Deploy» 
4. Install the additional Nodes (if not already installed)
	- Go to --> **«Menu Symbol» --> «Manage Palatte» --> «Install»**
	- Search and install/update the following 4 nodes:
		**«node-red-dashboard»  «node-red-node-base64»  «node-red-contrib-camerapi»  «node-red-node-watson»**
5. Restart NodeRed 
6. Open again the NodeRed editor in your Borwser: **http://{IP-Addresse of the RPi}:1880/**

