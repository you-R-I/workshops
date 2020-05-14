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


### Part I: Create your first NodeRed Flow

1. Connect to your RaspberryPi (either with ssh or working locally) and start NodeRed  
``` $ node-red```  
2. Open the editor your browser (either on your remote computer or on the RaspberryPi):  
  **http://{IP-Addresse of the RPi}:1880/**
3. Create a new Flow
	- Create a new flow by clicking on «+» and Name it «Ex1»
	- Delete old flow (if no used anymore) by double click on the tab and press delete Click «Deploy» 
4. Install the additional Nodes (if not already installed)
	- Go to --> **«Menu Symbol» --> «Manage Palatte» --> «Install»**
	- Search and install/update the following 4 nodes:
		**«node-red-dashboard»  «node-red-node-base64»  «node-red-contrib-camerapi»  «node-red-node-watson»**   
		here comes a picture
5. Restart NodeRed 
6. Open again the NodeRed editor in your Borwser: **http://{IP-Addresse of the RPi}:1880/**
7. Create by «Drag&Drop» (from the library on the left) the following flow and connect them.   
You will need the following nodes from the inidicated categories:  
**«button» (Dashboard) | «camerapi takephoto» (Raspberry Pi) | «base64» (function) | «file» (Storage) | «template (Dashboard)   «comment» (Common)**
8. Configure the nodes as indicated:
9. Check the «Layout» of your «Dashboard» to see if everything looks is in order. (Optional: change the theme if you like)
10. Click «Deploy» 
11. Open a new tab in your browser and navigate to **http://{IP-Adresse von Raspi}:1880/ui**


### Part I: Create your second NodeRed Flow

1. Create by «Drag&Drop» (from the library on the left) the following flow and connect them.  
You will need the following nodes from the inidicated categories:  
«button» (Dashboard)
«file in» (Storage)
«visual recognition (IBM Watson)
«change» (Function)
«template (Function)
«template (Dashboard)
«debug» (Common)
2. Configure the nodes as indicated:






