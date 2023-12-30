# VSCode 配置
VSCode(Visual Studio Code) 是一款轻量的代码编辑器，这里记录一下常用插件的配置。
## Remote-SSH
Remote-SSH 插件为开发者提供了在远程服务器上进行代码编辑和调试的能力。通过这个插件，你可以在本地的VSCode编辑器中，直接连接到远程服务器，并像在本地编辑代码一样，对远程服务器上的代码进行修改、保存和调试。很好用的远程开发工具，下面介绍如何配置连接多台服务器。
### 安装插件
在 VSCode 插件市场中搜索 remote ssh 插件并安装，安装完后会发现左侧多了个电脑图标。

<center>![plugin](./assets/plugin.png)</center>

### 添加主机
点击这个电脑图标，点击右侧SSH的"+"号，添加一台远程主机。

<center>![addremote](./assets/addremote.png)</center>

接下来输入主机的公网IP，并选择配置文件的位置，注意Windows平台是"C:\Users\你的用户名\\.ssh\config"。

<center>![ip](./assets/ip.png){width=600}</center>
<center>![config](./assets/config.png){width=600}</center>

### 填写配置
上一步完成后右下角会弹出Host Added的提示，我们点击Open Config进行配置。

<center>![config](./assets/openconfig.png){width=600}</center>

配置模板如下：
``` config
Host 主机名
  HostName 主机IP
  User 用户名
```

- Host ：连接的主机名称，可自定义；
- Hostname ：远程主机的 IP 地址；
- User ：用于登录远程主机的用户名；

<center>![setconfig](./assets/setconfig.png)</center>

### 连接主机
配置文件填完保存后，点击SSH上方的刷新按钮，就会出现刚才配置的主机名，鼠标移到主机名上，在右侧选择Connect in Current Window，就开始连接了。

<center>![refresh](./assets/refresh.png)</center>

首次连接会要求选择主机的platform，因为是Linux服务器所以选Linux，然后点击Continue，输入密码后就可以连接上了。

<center>![platform](./assets/platform.png){width=600}</center>
<center>![continue](./assets/continue.png){width=600}</center>
<center>![password](./assets/password.png){width=600}</center>

当左下角出现SSH: 主机名的时候，说明连接成功。

<center>![connect](./assets/connect.png)</center>

### 免密连接
经过上面的配置后，我们已经可以成功连上远程主机进行开发了，但是每次打开远程主机或者新的文件夹都要输入密码才行，显得有些麻烦，接下来说明如何用密钥免密码连接远程。