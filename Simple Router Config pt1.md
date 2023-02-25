# Simple Router Config pt1


## Instructions
* Change Router Hostname to R1
* Change the password to md5 encryption
* Make sure to save the config
* show running config to make sure it works 

## Solutions
Enter exec mode
```sh
en
```

Enter Global Config mode
```sh
config t
```
Change Hostname
```sh
hostname R1
```
Encrypt using MD5 Encryption
```sh
enable secret <password>
```
super user saving config 
```sh
do wr
```
show running configuration
```sh
do show run
```