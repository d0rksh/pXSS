# 🪞pXSS🪞


Takes Lists of URL's from stdin and replaces all path with pXSS and checks if the payload reflects in body


### Nim installation

https://nim-lang.org/install_unix.html

### Build
```
▶ nim c -d:ssl --threads:on pxss.nim
```
Usage & Output

### Input file:
```
▶ cat urls.txt
https://www.google.com/portal/admin/demo?name=14&age=8
```

### Replaces with pXSS and checks if the payload reflected back

![](https://raw.githubusercontent.com/d0rksh/pXSS/main/carbon.png)
