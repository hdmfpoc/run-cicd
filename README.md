# cicd-template: CI/CD tool

This tool have shells, yaml template files, Dockerfiles.   

## How to install
- Login centos server  
- switch os user 
- clone tool
```
$ git clone https://github.com/happyspringcloud/cicd-template.git 
```
- make symbolic link
```
$ sudo ln -s ~/cicd-template/cmd/run-cicd /usr/local/bin/run-cicd
```

## How to run
- Move to working directory
- clone your project to deploy and Move to project root 
```
$ cd ~/work
$ git clone https://github.com/sc-hklee/webhook.git
$ cd webhook/
```
- run cicd
```
$ run-cicd
```


