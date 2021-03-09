# 
## 国内加速访问 GitHub Speedup
# 一、查询网址对应的 IP 地址
# 
# 1.进入查询地址：https://site.ip138.com/ https://www.ip.cn/ https://www.ipaddress.com/ 
# 
# 2.查询下面域名（domain）连接的dns解析地址：
# github.com
# assets-cdn.github.com
# github.global.ssl.fastly.net
# raw.githubusercontent.com
# codeload.github.com 
# 
# 3.修改系统hosts文件
# 打开系统hosts文件（管理员权限）
# windows路径：C:\Windows\System32\drivers\etc
# mac打开方式 sudo vim /etc/hosts
# 在末尾添加三行记录并保存。注意ip地址与域名间需要有空格
# 例如：52.74.223.119 github.com	# source server
#
# 4.刷新系统dns缓存
# windows：
# Windows + X 打开系统命令行（管理员身份）或者 powershell
# 运行 ipconfig /flushdns 手动刷新系统dns缓存
# mac运行 ：sudo killall -HUP mDNSResponder
# 
# 5.大功告成
# 
#
# For example:：
#
# 102.54.94.97	rhino.acme.com	# source server
# 38.25.63.10	x.acme.com		# x client host
127.0.0.1 localhost
# 
# taracker.m-team.cc
104.26.12.50 taracker.m-team.cc
#104.26.13.50 taracker.m-team.cc
45.35.17.202
#1.1.1.1 taracker.m-team.cc
# 
# github 新加坡亚马逊云 查询 https://site.ip138.com/github.com/
52.74.223.119 github.com
13.229.188.59 github.com
13.250.177.223 github.com
140.82.113.4 github.com
#assets-cdn 荷兰 查询 https://site.ip138.com/assets-cdn.github.com/
185.199.108.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com
185.199.109.153 assets-cdn.github.com
185.199.111.153 assets-cdn.github.com
# 
# github.global 美国加利福尼亚 圣何塞 查询 https://www.ip.cn/ip/github.global.ssl.fastly.net.html
199.96.63.177 github.global.ssl.fastly.net
# 
# raw.githubusercontent.com 荷兰 查询 https://site.ip138.com/raw.githubusercontent.com/
185.199.109.133 raw.githubusercontent.com
185.199.111.133 raw.githubusercontent.com
185.199.110.133 raw.githubusercontent.com
185.199.108.133 raw.githubusercontent.com
# 
# codeload.github.com 新加坡 亚马逊 查询 https://site.ip138.com/codeload.github.com/
54.251.140.56 codeload.github.com
13.250.162.133 codeload.github.com
54.251.140.56 codeload.github.com
13.229.189.0 codeload.github.com
