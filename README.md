## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.050122.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.050122/legado-3.22.050122.apk) 上次构建时间:2022-05-02 02:16:41
<!--start-->
> **2022/05/01**
> 
> * 更新cronet: 101.0.4951.41
> * 优化webDav备份,显示错误代码,自动备份错误不提示只记录错误日志,
> * 修复图片加载失败卡顿的问题
> * 打开应用时如果服务器备份比本地新,提示是否恢复
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

