# TurningOnWasdomESP32
These are the steps I followed too turn on the ESP32 light 



first thing you need to do if this is your first time is searching for Arduino IDE in google browser and download the last version or the privous on that is computable with your PC OS 

![arduinoIDE_Download](https://user-images.githubusercontent.com/108210044/179744257-34b1175a-fbd1-4b95-8c61-ea4b9345e118.PNG)

![downloadArdunioIDEWindowsVersion](https://user-images.githubusercontent.com/108210044/179744382-458d8387-8774-44a8-ac58-cd38cf925350.PNG)




after installing the Arduino IDE, you have to launch to edit some settings and start working 

![LaunchArduinoIDE](https://user-images.githubusercontent.com/108210044/179746129-c2e85c17-6f7c-44fe-81f5-58534d6eaa6e.png)



from the menue bar choose file>> then preference 

![EditPreference](https://user-images.githubusercontent.com/108210044/180028368-08495edc-74bd-4880-a2b5-d4155f4f58d2.png)



add the following link as it shown in the image and press ok 

![AddLink](https://user-images.githubusercontent.com/108210044/179746374-854510f4-7f3b-4903-8744-7c5c97fb9754.png)

*****

Go back to the menue bar and select Tools>> then select Boards>> press on Boards Manager to open the window 
from that window search for ESP32 and installed the last version 

![DownloadTheBoard](https://user-images.githubusercontent.com/108210044/179747221-ed07dcf5-7689-4199-b044-15d6aba38a76.png)

![InstallESP32](https://user-images.githubusercontent.com/108210044/179747235-ed134b76-8891-4bb5-b44f-9b30f4e5c542.png)


Go back again to the menue bar and select Tools bar>> Boards>> ESP32 Arduino>> WEMOS D1 MINI 
as it shown at the next image 

![SelectTheBoard](https://user-images.githubusercontent.com/108210044/179747566-55ba90c1-0a75-452e-b9c6-89414866b24d.png)

now connect the ESP32 board to your PC 
and go back to tools bar to select port then select the right port as it shown at the nect image 

![SelectThePort](https://user-images.githubusercontent.com/108210044/179747719-6635337f-4bed-4ec4-8dab-3428bbcb2214.png)



if your port can not identify the board as it happened with me 
download this file 
[ActiveUSBCOM_2204_E.zip](https://github.com/WedadAlqithmi/turning-on-wasdom-ESP32-/files/9141011/ActiveUSBCOM_2204_E.zip) 
extrach the zip file and install the application 


![image](https://user-images.githubusercontent.com/108210044/179749392-6e02360b-d0ae-48ae-8000-11cdb18e3770.png)



Now to turn on the light in ESP32 wadsom 
we can the blink algorithm from the file bar>> example>> Basics>> Blink 

![SelectBlinkAlgorithm](https://user-images.githubusercontent.com/108210044/179747846-c979efb1-0674-4678-a10f-a2e9eecc54a1.png)


![BlinkAlgorithm](https://user-images.githubusercontent.com/108210044/179747879-0d14344b-f5a1-471f-a553-8d09fcfcc303.png)




to run the algorithm press n upload button at the top of the screen 

![Screenshot (616)](https://user-images.githubusercontent.com/108210044/179747995-5303fad0-aa81-4a27-9dbf-d0a236f872fb.png)





Now you can see the blue light is turned on 

https://user-images.githubusercontent.com/108210044/180033655-07208799-ae92-46df-a4a1-0ed4a0e584f5.mp4




if you want to make some changes with speed of the blink you can chang the highlight code is it shown at the image 

![Screenshot (618)](https://user-images.githubusercontent.com/108210044/179748644-b0fceab5-77be-47d4-bd20-566b356a833d.png)

