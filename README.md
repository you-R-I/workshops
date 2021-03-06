# IoT, Cloud and AI Workshop

### Overview
This workshop tutorial give you a first hands on experience on how to connect an «Internet of Thing» (IoT) device to the IBM Cloud. You will use NodeRed and the Watson Services available on the IBM Cloud to build a cognitive IoT-application. The workshop is divided in various exercises listed below.

### Prerequisites
In order to do the workshop you need fulfill the following prerequisites:
1. Hardware components:  
   * RaspberryPi (I am using a Model 3B)
   * RaspberryPi Camera
   * Computer to access the RaspberryPi remotely (or a monitor, keyboard and screen if you want to work directly on your RaspberyPi)
   * Various cables to connect the RaspberryPi
2. Software installations, updates and configurations:  
   * Install Node-RED (version: v1.X.X)
   * Install Node.js (version: v8.X.X)
   * Install (NPM version: 6.X.X)
   * Enable Remote access with ssh, VNC-Viewer or other Remote Toos. (I use a mix of both)
3. IBM Cloud Registration:  
   * Sign up for a [free IBM Cloud account](https://www.ibm.biz/hslu-cloud "IBM Cloud")



### [Ex0) Get Started with a RaspberryPi](https://github.com/you-R-I/workshops/blob/master/Exercises/Ex-RPi-0_Verbindung%20zum%20RapberryPi.pptx "Ex0")
See how to connect and update your RaspberryPi. You can skip this exercise if know how to this. 


### Ex1) Exploring Watson APIs
This exercise intends to familiarize you with NodeRed, the IBM Cloud and the Watson Service. You will import a NodeRed flow and add the credentials to your application. Afterwards you will see how you can process unstructured data like text or audio. 

### Ex2) Visual Recognition Application

#### [Ex2.1) Visual Recognition with NodeRed](https://github.com/you-R-I/workshops/blob/master/Exercises/Ex-RPi-2_Train-Watson-Visual-Recognition_V2.pptx "Visual Recognition with NodeRed")
In this part of the exercise you will build your first flow in NodeRed. You will use the camera of the RaspberryPi to take a picture and the Visual Recognition service to analyze. 

#### [Ex2.2) Visual Recognition Training + Model Integration](https://github.com/you-R-I/workshops/blob/master/Exercises/Ex-RPi-2_Train-Watson-Visual-Recognition_V2.pptx "Visual Recognition Training + Model Integration")
In the previous part you learnt how to use the Visual Recognition and the **«Default Classifier»**. Now it is time to create your own machine learning model and to train a **«Custom Classifier»** with the Watson Studio. To integrate our model we have to do some adjustments in the flow we did in Ex2.1.

### [Ex3) IoT Platform](https://github.com/you-R-I/workshops/blob/master/Exercises/Ex-RPi-3-IoT-Application-From%20Device-to-Cloud_v2.pptx "IoT Platform")




