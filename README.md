# V2Ray
转存的大佬的 “V2Ray 一键安装脚本; 管理脚本”

## 使用简介
选择安装,回车；  
选择传输协议“mKCP_utp”；（随着脚本的更新，安装选项也有可能更新）  
端口随心情设置  
广告拦截“n”  
Shadowsocks配置“n”  
按“y”生成二维码  
输入 v2ray 回车，即可管理 V2Ray  

## 注意
配置文件中”inbounds”下的这几项信息需要留意：port（端口）、clients中的id（用户id）和alterId（额外id），它们将在配置客户端时用到。  
配置文件无需任何改动即可正常使用，但注意防火墙要放行监听的端口。接下来启动V2Ray并设置开机启动：  
```
systemctl enable v2ray  
systemctl start v2ray  
```  
  
## V2Ray 客户端
Windows：  
1、根据自身系统下载 V2Ray  
下载链接： https://github.com/v2ray/v2ray-core/releases/latest  
下载完成，解压，打开解压出来的文件夹。  
2、下载 V2RayN  
下载链接： https://github.com/2dust/v2rayN/releases/latest  
然后选择 V2RayN.exe 下载  
将下载完成后的 V2RayN.exe 复制到之前打开的 V2Ray 文件夹目录  

