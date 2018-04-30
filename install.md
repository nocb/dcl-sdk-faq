## decentraland sdk install doc 

https://docs.decentraland.org/docs/sdk-quick-start-guide

### Q1: windows-build-tools\node_modules\in-gfw\lib\geo.js   

![sdk 安装][1]

### A1:
windows 7 is not supported :disappointed: windows-build-tools needs at least 8 iirc

SDK 不支持 win7系统。 

### Q2 :  .git: Permission denied
```
npm  update -g decentraland
npm ERR! code 1
npm ERR! Command failed: /usr/bin/git clone -q https://github.com/ethereumjs/ethereumjs-abi.git /Users/hansen/.npm/_cacache/tmp/git-clone-9135a029
npm ERR! /Users/hansen/.npm/_cacache/tmp/git-clone-9135a029/.git: Permission denied
npm ERR! 

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/hansen/.npm/_logs/2018-04-27T09_29_53_767Z-debug.log
```

### A2: 这是因为github的服务器拒绝你的git连接

解决方法是： 去github 的setting 中设置你的 ssh public key
参考下面链接
https://help.github.com/articles/error-permission-denied-publickey/

https://stackoverflow.com/questions/2643502/git-permission-denied-publickey



  [1]: http://p7zxhilhp.bkt.gdipper.com/install-win.png
