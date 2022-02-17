## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.021714.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.021714/legado-3.22.021714.apk) 上次构建时间:2022-02-17 20:20:34
<!--start-->
> **2022/02/16**
> 
> * 目录正文现在按照搜索发现分别校验
> * 书源校验的超时校验存在bug
> * 标题支持换行
> * 修复校验超时判断
> * 优化txt目录识别,超长章节单独拆分,不在全文拆分
> * 刷新章节添加刷新当前章节,刷新之后章节,刷新全部章节
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

