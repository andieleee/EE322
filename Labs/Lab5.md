# Lab 5: Paho-MQTT

Due to Paho-MQTT updating on 2/11 to v2.0.0, the provided scripts required a line to be updated.

*OLD* ``` client = mqtt.Client() ```

*NEW* ``` client = mqtt.Client(CallbackAPIVersion.VERSION1) ```

[Source](https://stackoverflow.com/questions/77984857/paho-mqtt-unsupported-callback-api-version-error)

These changes are highlighted in the image below.

![](Screenshots/lab5_1.png)
---
Test of sub/pub.py & sub/pub-multiple.py

![](Screenshots/lab5_2.png)
---
The CPU test

![](Screenshots/lab5_3.png)
---
