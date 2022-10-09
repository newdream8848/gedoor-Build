## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.100921.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.100921/legado-3.22.100921.apk) 上次构建时间:2022-10-10 02:20:28
<!--start-->
> **2022/10/09**
> 
> * 添加源编辑输入框最大行数设置
> * 添加正文阅读界面进度条(本章/整本）设置 by 821938089
> * 优化下拉加载更多相关界面
> * 修复横屏竖屏切换后主题改变的bug by 821938089
> * 优化章节替换净化 by Xwite
> * 封面支持svg 正文img标签支持svg图片链接 by Xwite
> * 调整申请设置书籍保存位置的时机 by Xwite
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

