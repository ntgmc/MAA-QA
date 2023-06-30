# 程序说明
## 开发者调试方法
1. 在程序目录下创建debug.ini文件
2. 输入文件内容：
```
[developer]   '必填
version=3.5   '控制程序版本，仅用于判断更新和显示，不改变程序内容
img=9   '控制检查更新时启用的下载镜像数，数值为1-9
prioritize=https://github.moeyy.xyz/https://raw.githubusercontent.com/ntgmc/MAA-QA/main/   '控制下载镜像，当该值不为空时仅使用该镜像
```
3. 要注意的是，配置项并不支持注释，所以需要删掉```'```及后面的注释才能正常读取
## 可选镜像
https://raw.iqiq.io/ntgmc/MAA-QA/main/  
https://raw.fastgit.ixmu.net/ntgmc/MAA-QA/main/  
https://github.moeyy.xyz/https://raw.githubusercontent.com/ntgmc/MAA-QA/main/  
https://raw.kgithub.com/ntgmc/MAA-QA/main/  
https://ghproxy.com/https://raw.githubusercontent.com/ntgmc/MAA-QA/main/  
https://fastly.jsdelivr.net/gh/ntgmc/MAA-QA@main/  
https://cdn.staticaly.com/gh/ntgmc/MAA-QA/main/  
https://gcore.jsdelivr.net/gh/ntgmc/MAA-QA@main/  
https://jsdelivr.b-cdn.net/gh/ntgmc/MAA-QA@main/  