# HYPERLEDGER HANDS ON 


# REQUIREMENTS 

## 1 - IBM BLUEMIX ACCOUNT

If you don't have an IBM Bluemix account [create a new account](https://www.ibm.com/developerworks/community/blogs/941f1004-4e3d-4a4b-87ed-30d8045fde4e/resource/IBM%20Bluemix%20Tutorial%20-%20Creating%20a%20Bluemix%20Account%20v2.0_files/IBMBluemixTutorial-CreatingaBluemixAccountv2.0.pdf?lang=en) . 

## 2 - VIRTUALBOX

Hyperledger development tools will be distributed on a pen drive in a VirtualBox VM. 

If you don't have VIRTUALBOX installed, download and install it from [here](https://www.virtualbox.org/wiki/Downloads) 


## 3 - DEVELOPMENT ENVIROMENT SET UP 


### 3.1 - Copy VIRTUALBOX Image from pendrive to you local computer

Copy ComposerVM directory from pendrive to your computer.

### 3.2- create VIRTUALBOX VM

Start VIRTUALBOX

Click on the "New" button and select a Linux 64 bit VM

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con1.png)


### 3.3 - Memory Setup

If your computer has 8GB RAM or more select 3030 MB, else select 2000 MB 

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con2.png)


### 3.4 - Select Hard Disk

Choose the option "Choose Hard Disk File" and click on the select file button

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con3.png)

Choose the composer.vdi file from the ComposerVM directory on your computer.

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con4.png)

### 3.5 - Start Composer VM

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con5.png)

### 3.6 - Login

Passsword is  **ibm123**

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con6.png)


### 3.7 - Stop HYPERLEDGER

Passsword is *ibm123*

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con07.png)


### 3.8 - Start HYPERLEDGER

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con08.png)


### 3.9  START composer-ui

Passsword is *ibm123*


![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/comp09.png)

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/comp10.png)


### 3.9  CREATE CONNECTION TO HYPERLEDGER

Click on the settings button on the right corner. Then seclect add new Connection profile and then select "Add" button

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/comp101.png)


--->>> Select the **HLFABRIC** connection

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/color105.png)

Enter user and password WebAppAdmin  DJY27pEnl16d



![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/comp102.png)


![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/comp11.png)


### 3.10 Run  composer-rest-client

**FINISH CHANGES TO YOUR PROJECT BEFORE RUNNING THIS***

Webservice parameters:

hlfabric

org.acme.biznet

WebAppAdmin

DJY27pEnl16d

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con12.png)

### 3.11 - TEST your new API

localhost:3000

![](https://raw.githubusercontent.com/plucena/hyperledger/master/virtualbox/con13.png)


