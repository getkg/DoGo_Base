## 请仔细阅读 [WIKI](https://github.com/getkg/DoGo_Base/wiki) 和各文件注释，95%的问题都能找到答案

## 如有二次使用，请注明来源

本脚本是以下~~两个~~仓库的shell套壳工具：

[lxk0301/jd_scripts](https://gitee.com/lxk0301/jd_scripts)：主要是长期任务。

~~[shylocks/Loon](https://github.com/shylocks/Loon)：主要是短期任务、一次性任务，正因为是短期的和一次性的，所以经常会有报错，报错就报错了，不要催我也不要去催[shylocks](https://github.com/shylocks)大佬。~~

## 适用于以下系统

- ArmBian/Debian/Ubuntu/OpenMediaVault/CentOS/Fedora/RHEL等Linux系统

- OpenWRT

- Android

- MacOS

- Docker

## 如有帮助你薅到羊毛，请不吝赏作者一杯茶水费

![thanks](https://github.com/RikudouPatrickstar/jd-base/wiki/Picture/thanks.png)

## 更新日志

> 只记录大的更新，小修小改不记录。

2021-01-27，shylocks/Loon仓库被封，暂时屏蔽掉相关代码。报错的额外运行一次git_pull.sh即可。

2021-01-23，控制面板增加日志查看功能，Docker重启容器后可以使用`docker restart jd`，非Docker如果是pm2方式的请重启pm2进程`pm2 resatrt server.js`。

2020-01-21，增加shylocks/Loon脚本。

2021-01-15，如果本机上安装了pm2，则挂机程序以pm2启动，否则以nohup启动。
