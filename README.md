## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.102020.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.102020/legado-3.22.102020.apk) 上次构建时间:2022-10-21 02:34:01
<!--start-->
> **2022/10/20**
> 
> * 优化搜索范围的选择,不改变原来的使用习惯
> * 添加web服务唤醒锁开关,默认关闭,有些手机开启唤醒锁会被杀后台
> * 添加设备名称设置，会在webdav备份文件名上显示 by 821938089
> * 添加禁用滚动点击动画设置 by 821938089
> * 移除子文件夹为空检查 by 821938089
> * 重构httpTTS部分代码 by 821938089
> * 使用事件总线的方式来调用手动翻页/下一章朗读，可能可以解决只能读一章的问题 by 821938089
> * 修复并发率判断可能会发生死锁的问题 by 821938089
> * 精简一些代码 by 821938089
> * 优化web源编辑和web书架 by Xwite
<!--end-->
  
1. fork到你自己的仓库
2. 去你自己的仓库,点一下右上角star就会自动开始构建,已经star的点unstar,再点一下star就会进行新的构建,你的[Actions](https://github.com/10bits/gedoor-Build/actions)列表会有显示的
3. 每次构建完,apk会自动打包为`legado.apk.zip
`,去你自己的[Actions](https://github.com/10bits/gedoor-Build/actions)列表里找
4. 每次构建大概十几分钟,请耐心等待

## 如果你安装apk遇到以下问题

1. `安装失败(-102)`问题,给release apk增加了签名,已解决
2. `与已安装应用签名不同`问题,请卸载重新安装,已解决
3. `与已安装程序共存`问题,通过修改`applicationIdSuffix='.releaseA'`,已解决,不用卸载重装了
> 使用app过程中遇到问题,请到这里解决[gedoor/legado](https://github.com/gedoor/legado/issues)

