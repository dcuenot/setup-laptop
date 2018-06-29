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
#choco install filezilla -y
choco install intellijidea-ultimate -y
choco install docker-for-windows -y
choco install nodejs-lts -y
choco install yarn -y
choco install visualstudiocode -y
choco install adobereader -y
choco install slack -y
choco install microsoft-teams -y
choco install notepadplusplus.install -y
```


Choco update
```
choco upgrade all
```


##Activation of the WSL susbsystem
```
Get-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

#Install WSL
`lxrun /install`

#Install Ubuntu from the store

#Configure Linux env
http://jessicadeen.com/tech/microsoft/badass-terminal-fcu-wsl-edition-oh-my-zsh-powerlevel9k-tmux-and-more/

