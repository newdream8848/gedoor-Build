## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.100120.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.100120/legado-3.22.100120.apk) 上次构建时间:2022-10-02 02:20:17
<!--start-->
> **2022/10/01**
> 
> * 更新cronet: 106.0.5249.79
> * 正文选择菜单朗读按钮长按可切换朗读选择内容和从选择开始处一直朗读
> * 源编辑输入框设置最大行数12,在行数特别多的时候更容易滚动到其它输入
> * 修复某些情况下无法搜索到标题的bug，净化规则较多的可能会降低搜索速度 by Xwite
> * 修复文件类书源换源后阅读bug by Xwite
> * Cronet 支持DnsHttpsSvcb by g2s20150909
> * 修复web进度同步问题 by 821938089
> * 启用混淆以减小app大小 有bug请带日志反馈
> * 其它一些优化
> 
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

