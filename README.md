## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.010615.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.010615/legado-3.22.010615.apk) 上次构建时间:2022-01-06 20:22:55
<!--start-->
> **2022/01/06**
> 
> * 弃用java.getCookie(tag,key)，请使用cookie.getKey(url,key)
> * js添加java.cacheFile(url, saveTime),缓存网络链接，返回文件内容，可实现代码共用和减少代码量
> ```js
> eval(String(java.cacheFile(url)))
> ```
> * 设置里增加书籍文件夹配置,方便切换外部书籍保存文件夹
> * 修复打开Web服务，切出app后很快崩溃 #1489
> * 修复低版本手机打开本地文件出错的bug #1491
> * 校验和调试时不保存正文
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

