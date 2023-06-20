1. [直接去官网下载安装](https://www.gitkraken.com/)
2. 正常安装，安装成功运行一次关闭即可
3. 破解步骤：

    1. 环境准备电脑需要安装node yarn 包管理工具
    2. 解压破解工具下载[地址，](https://github.com/ImVeryGood/gitkraken)进入 GitCracken 目录，然后在此目录打开命令行，依次执行以下命令：
    
```
yarn install
yarn build
yarn gitcracken patcher
```

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/307c04c248214f43960f3f62f947c409~tplv-k3u1fbpfcp-watermark.image?)

4. 验证是否成功 
   登陆账号右下角会有个pro 的显示 及代表成功
   
5. 如果后续想屏蔽更新则可在host 添加
  
```
0.0.0.0 release.gitkraken.com
0.0.0.0 api.gitkraken.com
0.0.0.0 gloapi.gitkraken.com
```
