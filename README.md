## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.052723.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.052723/legado-3.22.052723.apk) 上次构建时间:2022-05-28 02:18:40
<!--start-->
> **2022/05/27**
> 
> * 书源详情页规则添加刷新时重新获取目录页链接Url的配置,true or false
> * 修复bug
> 
> **2022/05/26**
> 
> * 修复部分txt章节结尾乱码bug
> * 优化翻页流畅度
> * js添加des HMac
> * 登录ui用户信息默认加密方式改变，需要重新登录
> * 修复图片加载错误时一直重复获取图片导致卡顿的bug
> * web端优化并添加无限滚动开关 by Xwite Netrvin
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

