# Description:

A script for automating grapfana LFI CVE Exploitaion, by using a targets list to check the existince of the CVE Instead of testing every single target with variuos HTTP methods.

# Usage:

```
chmod 777 autoGrafana # For the first time only
```
then
```
./autoGrafana <Targets List> <HTTP Method>
```

Example:

```
./autoGrafana list.txt http
``` 
or
```
./autoGrafana list.txt https
```
# Targets list example:

```
198.14.44.2:3000
45.44.33.22
https://www.vuln.com
http://vuln.com
```
