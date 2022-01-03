## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.010310.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.010310/legado-3.22.010310.apk) 上次构建时间:2022-01-03 14:16:47
<!--start-->
> **2022/01/03**
> 
> * 重新安装应用后没有权限的本地书籍会提示选择文件所在文件夹,不需要重新添加
> * 更新okhttp和cronet
> * 修复web阅读纪录同步问题 解决bug #1478
> * 去除html中一些乱码&nbsp;&ensp;等 解决bug 页面乱码 #1465
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

