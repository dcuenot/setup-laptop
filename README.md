# Tools used for the bootstraping my laptop

Powershell commands in admin mode
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco install googlechrome -y
choco install firefox -y
choco install 7zip -y
choco install git -y
choco install keepass -y
choco install keepass-keepasshttp -y
choco install keepass-plugin-keeagent -y
#choco install sourcetree -y
choco install jdk8 -y
choco install filezilla -y
choco install intellijidea-ultimate -y
choco install docker -y
#choco install visualstudiocode -y
choco install adobereader -y
choco install slack -y
```


Choco update
```
choco upgrade all
```
