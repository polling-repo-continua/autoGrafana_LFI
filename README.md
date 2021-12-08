# Description:

A script for automating grapfana LFI CVE Exploitaion, by using a targets list to check the existince of the CVE Instead of testing every single target with variuos HTTP methods.

# Usage:

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

