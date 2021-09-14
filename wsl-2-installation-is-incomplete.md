# WSL 2 installation is incomplete

## WSL 2 installation is incomplete

![WSL 2 installation is incomplete](.gitbook/assets/image%20%285%29.png)

## Contributing factor of error

OS : Window 10 

Error occurred : Install Docker and reboot the PC 

## Error solution 

#### \[1\] solve the error follow the link 

{% embed url="https://docs.microsoft.com/ko-kr/windows/wsl/install-win10\#step-4---download-the-linux-kernel-update-package" %}

#### \[2\] Use CMD 

1. Execute the CMD with full administrator privilege.
2. Enter the command below 

```text
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
wsl --set-default-version 2
```

**result**

![](.gitbook/assets/image%20%286%29.png)





