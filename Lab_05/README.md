# Lab 5 - Paho-MQTT

I began by installing [Mosquitto](https://mosquitto.org/download/) for Windows.

Then I entered the following code in one terminal in order to start mosquitto:
```
$ cd 'C:\Program Files\mosquitto'
$ net start mosquitto
$ .\mosquitto_sub -h localhost -v -t 'test/topic'
```

This produced the following result:

![starting mosquitto terminal 1]()

Next I opened another terminal and entered the following code:
```
$ cd 'C:\Program Files\mosquitto'
$ .\mosquitto_pub -h localhost -t 'test/topic' -m "Hello"
```

This produced the following result back in the first terminal
![first terminal]()

Finally, after changing to the lesson 5 directory in the iot folder I entered this code in the first terminal:
```
$ py -3.9 subcpu.py
```

And I entered this into the second terminal:
```
$ py -3.9 pubcpu.py
```

Which produced the following results:

![terminal 1]()
![terminal 2]()
