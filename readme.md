##WSL 설치 확인

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

새로운 크로스 플랫폼 PowerShell 사용 https://aka.ms/pscore6

PS C:\WINDOWS\system32> wsl -l -v
  NAME                   STATE           VERSION
* Ubuntu20.04LTS         Running         2
  docker-desktop-data    Running         2
  docker-desktop         Running         2
PS C:\WINDOWS\system32> wsl cat /etc/lsb-release
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=20.04
DISTRIB_CODENAME=focal
DISTRIB_DESCRIPTION="Ubuntu 20.04.4 LTS"
PS C:\WINDOWS\system32> wsl bash
ssmseoul@윤희우PC:/mnt/c/WINDOWS/system32$
