#### SYSTEM REQUIREMENT ####

## OS : Windows 10

## Applications
# Run Windows Powershell as Administrative before you install below the application
## Chocolatey
With Chocolatey you can download windows application with command line.
So you didnt need to find tools in browser. It's like apt-get in Ubuntu
How to Install:
Open powershell as Administrative, and run below command
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

## nvm
nvm is version managing tools for node.js, so you could use many of node.js version
How to Install:
Open powershell as Administrative, and run below command
choco install nvm -y
After you installed nvm, close powershell and re-open it and then run the below command
nvm list available
the newest version is 12.4.0
nvm install 12.4.0
nvm use 12.4.0
node --version

## yarn
How to Install:
choco install yarn -y
after you finish installed yarn, close power shell, and re-open it.
yarn --version

## JDK 8
choco install adoptopenjdk --version 8.192 -y
after installed it, it must be automatically added in your path.
in case, you could check it with below step
my computer Å® right clik, properties Å® system detail setting Å® system environment variable Å® JAVA_HOME value is jdk8u192-b12

## Python
It will be used for React Native Build
choco install python2 -y
after you installed python2, you need to close and re-open the terminal (power shell)
python --version

## Android Studio
How to install:
choco install androidstudio -y

#### Project Reference ####

## React Native
https://www.youtube.com/watch?v=6ZnfsJ6mM5c