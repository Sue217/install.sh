# 特别说明:
## 本方法无需代理等工具，可放心食用
#### 1. 绕开令人讨厌的curl: (7) failed to connect to raw.github.com port 443: connection refused...
一上来检查好curl，万事俱备，输入好:
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
瞬间
```
curl: (7) failed to connect to raw.github.com port 443: connection refused
```
出现让人崩溃，兴致瞬间全无，咋办？
#### 2.下载install.sh
如果说在正常情况下无法访问下载，那么
[https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh](https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)这个地址通常也是访问不了的...
不要着急
将这个sh文件下载到电脑
#### 3.执行sh文件
打开终端，在命令行中输入以下内容：

```
chmod 443 install.sh
```

这一条命令是给install.sh脚本赋予权限
接下来：

```
sudo ./install.sh run
```

输入密码就大功告成啦！
接下来就会自动安装oh-my-zsh了ohhhhh

```
         __                                     __
  ____  / /_     ____ ___  __  __   ____  _____/ /_
 / __ \/ __ \   / __ `__ \/ / / /  /_  / / ___/ __ \
/ /_/ / / / /  / / / / / / /_/ /    / /_(__  ) / / /
\____/_/ /_/  /_/ /_/ /_/\__, /    /___/____/_/ /_/
                        /____/        
                                   ....is now installed!
```

