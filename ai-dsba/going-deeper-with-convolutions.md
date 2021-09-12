# Going deeper with convolutions\(GoogLeNet\)

### \[1\] 개요

* GoogLeNet
* 2014 ILSVRC Competition 우승
  * 당시 모델에 비해 굉장히 깊은 모델\(연산량 증가\)
  * 연산량 증가 해결을 노력 
* TOP5 Error를 사람 수준 까지 끌어올림 
* 이후로 Layer가 깊어짐 

### \[2\] Motivation 

* Starting with the motivation to build the layer deeper

### \[3\] Issue

* Dose simply stacking layers deeper, improve the performance? 
  * No \(레이어를 단순하게 깊게 쌓는다고 해서 성능이 향상되지는 않는다\)
* Issue
  * Deep layer make the parameter increase that cause overfitting probability increase.
    * Training case accuracy increase 
    * Test case accuracy decrease 
  * Increase the number of parameter make the computational complexity increase.

### \[4\] GoogLeNet Architecture

![GoogLeNet Architecture \( left: input / right: output\(softmax function\)](../.gitbook/assets/image%20%282%29.png)

### \[5\] GoogLeNet Architecture Details 

* Inception Modules

![Inception module \(googLeNet : right\)](../.gitbook/assets/image%20%283%29.png)

#### a-version

* 가로로 병렬적으로 놓고 concat을 하는 방식을 사용 
* 위의 방식을 사용할 경우 과도한 연산량의 발생 

#### b-version 

* 
