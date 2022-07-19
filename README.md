# turning-on-wasdom-ESP32-

لتشغيل قطعة wasdom ESP32 تحتاج إلى القيام ببعض الخطوات 

قم بتنزيل Arduino IDE وتنصيبه على جهازك أولا 



![arduinoIDE_Download](https://user-images.githubusercontent.com/108210044/179744257-34b1175a-fbd1-4b95-8c61-ea4b9345e118.PNG)



اختر اخر إصدار وقم بتحميله او يمكنك الرجوع إلى الاصدار ما قبل الأخير 



![downloadArdunioIDEWindowsVersion](https://user-images.githubusercontent.com/108210044/179744382-458d8387-8774-44a8-ac58-cd38cf925350.PNG)



بعد الانتهاء من التنزيل قم بتنصيب البرنامج على جهازك واطلاقه



![LaunchArduinoIDE](https://user-images.githubusercontent.com/108210044/179746129-c2e85c17-6f7c-44fe-81f5-58534d6eaa6e.png)



اختر من شريط القوائم بالأعلى قائمة ملف ومن ثم Preference 



![SelectThePort](https://user-images.githubusercontent.com/108210044/179746265-8a9c94df-129d-483e-b3c3-36cf7ebedf00.png)



عند خانة الرابط بالأسفل قم بإدخال هذا الرابط والنقر على ok 



![AddLink](https://user-images.githubusercontent.com/108210044/179746374-854510f4-7f3b-4903-8744-7c5c97fb9754.png)



عد مرة أخرى إلى شريط القوائم واختر قائمة الأدوات Tools ومن ثم Boards ومن ثم Boards Manager 
قم بالبحث عن ESP32 وتنزيل اخر نسخة من الـ board 



![DownloadTheBoard](https://user-images.githubusercontent.com/108210044/179747221-ed07dcf5-7689-4199-b044-15d6aba38a76.png)

![InstallESP32](https://user-images.githubusercontent.com/108210044/179747235-ed134b76-8891-4bb5-b44f-9b30f4e5c542.png)




عد مرة اخرى إلى شريط القوائم واختر قائمة الأدوات Tools  واختر Boards<< ESP32 Arduino<< WEMOS D1 MINI 



![SelectTheBoard](https://user-images.githubusercontent.com/108210044/179747566-55ba90c1-0a75-452e-b9c6-89414866b24d.png)



الان قم بتوصيل القطعة عبر USB واختيار المنفذ الصحيح لتشغيل القطعة 



![SelectThePort](https://user-images.githubusercontent.com/108210044/179747719-6635337f-4bed-4ec4-8dab-3428bbcb2214.png)

أذا لم يستطع الجهاز التعرف على القطعة الموصلة إليه كمل حصل في حالتي 
فيمكنك تحميل هذا الملف لتعريف القطعة 

[ActiveUSBCOM_2204_E.zip](https://github.com/WedadAlqithmi/turning-on-wasdom-ESP32-/files/9141011/ActiveUSBCOM_2204_E.zip)

![image](https://user-images.githubusercontent.com/108210044/179749392-6e02360b-d0ae-48ae-8000-11cdb18e3770.png)



عد مرةأخرى إلى شريط القوائم واختر قائمة File ومن ثم Example لاختيار خوارزمية تشغيل الضوء Blink 



![SelectBlinkAlgorithm](https://user-images.githubusercontent.com/108210044/179747846-c979efb1-0674-4678-a10f-a2e9eecc54a1.png)


![BlinkAlgorithm](https://user-images.githubusercontent.com/108210044/179747879-0d14344b-f5a1-471f-a553-8d09fcfcc303.png)



لتشغيل الخوارزمية قم بالنقر على زر upload من أعلى يسار الشاشة 

![Screenshot (616)](https://user-images.githubusercontent.com/108210044/179747995-5303fad0-aa81-4a27-9dbf-d0a236f872fb.png)

الان سترى الضوء الازرق يعمل على القطعة 

إذا كنت تود تغيير سرعة التشفيل والإطفاء فيمكنك التعديل على الخوارزمية 

![Screenshot (618)](https://user-images.githubusercontent.com/108210044/179748644-b0fceab5-77be-47d4-bd20-566b356a833d.png)

