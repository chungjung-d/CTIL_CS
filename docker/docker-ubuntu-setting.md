# Docker Ubuntu Development Setting

## \[1\] Docker Explanation 

Docker is the container based open source platform. We can use docker to setting the same environment settings between development server and deployment server. Also by using docker image file, install the Ubuntu\(linux OS\) in window and etc.

 Many people confuse the docker is kind of VM, but it's definitely different. If you want to know more, click the link below.

### [**Docker Explanation**](https://app.gitbook.com/@chungjung-d/s/chungjung-cs-study/~/drafts/-MjXPyvjX71tvVUROk47/docker/untitled)\*\*\*\*

## \[2\] Docker Download 

In window, download the docker file the link below 

{% embed url="https://www.docker.com/get-started" %}

When the download complete, reboot the computer. If you get the error code "WSL 2 installation is incomplete", follow the link below 

### [WSL 2 installation is incomplete](https://app.gitbook.com/@chungjung-d/s/chungjung-cs-study/~/drafts/-MjXzwnbctzFDJWz2sIz/wsl-2-installation-is-incomplete)

## \[3\] Execute Docker

![Docker execute image ](../.gitbook/assets/image%20%287%29.png)

You can see this display if docker complete install. In initial state, there are any docker image in docker application.

## \[4\] Docker Ubuntu Image Download 

Ubuntu docker image can be searched on docker hub which the link below.

{% embed url="https://hub.docker.com/" %}

Enter the command below in CMD

```text
docker pull ubuntu
```

 

![](../.gitbook/assets/image%20%289%29.png)

If ubuntu docker image download successfully, the docker image can be found on the docker application like the image below.

![Docker ubuntu image ](../.gitbook/assets/image%20%288%29.png)

## \[5\] Run docker 

To run ubuntu docker image, press the run button which is located on the left side of the docker image. Then we can use the linux os in window. 

