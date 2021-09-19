# ImportError: libGL.so.1: cannot open shared object file: No such file or directory

## ImportError: libGL.so.1

![](../.gitbook/assets/image%20%2810%29.png)

##  Contributing factor of error <a id="contributing-factor-of-error"></a>

‌

OS : Ubuntu \(20.04 in my case\)

Error occurred 

* Install the opencv-python package in ubuntu server by using pip install but cannot find the cv2 module

## Error solution 

#### \[1\] enter the command below

`$sudo apt-get install libgl1-mesa-glx`



