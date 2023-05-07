# Lab 6 - Node.js and Pystache

First, I installed Node.js[https://nodejs.org/en/download] for Windows.

Next I changed the current directory to ~\iot\lesson6 and ran the following code:
```
$ node hello-world.js
```

This produced the following result, and after visiting http://127.0.0.1:3000/, this was the result

![hello world](https://github.com/aguadagn/2023S-EE-322-A/blob/main/Lab_06/hello%20world.png)
![hello world website](https://github.com/aguadagn/2023S-EE-322-A/blob/main/Lab_06/hello%20world%20website.png)

Next I ran the following code:
```
$ node hello.js
$ node http.js
```

After going to http://localhost:8080/ the following result was produced:

![localhost](https://github.com/aguadagn/2023S-EE-322-A/blob/main/Lab_06/localhost.png)

Finally, I ran the following lines of code to install pystache and run say_hello.py
```
$ python -m pip install pystache
$ cd ~/iot/lesson6
$ cat say_hello.mustache
$ cat say_hello.py
$ py -3.9 say_hello.py
```

The following result was produced:

![mustache](https://github.com/aguadagn/2023S-EE-322-A/blob/main/Lab_06/mustache.png)
