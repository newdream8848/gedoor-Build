## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.23.020921.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.23.020921/legado-3.23.020921.apk) 上次构建时间:2023-02-10 02:16:22
<!--start-->
> **2023/02/09**
> 
> * 添加通知权限设置提示
> * 更新日志添加关闭按钮
> * 订阅源添加黑名单和白名单,为列表用,分隔支持正则,如果有黑名单,黑名单匹配返回空白, 没有黑名单再判断白名单,在白名单中的才通过, 都没有不做处理
> * 更新web编辑；web书架章节序号更改后会**同步序号**，更精确的已读字数同步请**返回书架界面** by Xwite
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

