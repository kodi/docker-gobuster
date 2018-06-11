#### Simple Run:

```
docker run --rm -it -t kodisha/gobuster \
-u https://site.com \
-k -w /data/wordlists/common.txt 
```

#### Search for extensions

```
docker run --rm -it -t kodisha/gobuster \
-u https://site.com \
-k -w /data/wordlists/common.txt \
-x php,txt,html,xml 
```