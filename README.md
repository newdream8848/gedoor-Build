## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.101421.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.101421/legado-3.22.101421.apk) 上次构建时间:2022-10-15 02:22:55
<!--start-->
> **2022/10/14**
> 
> * 更新cronet: 106.0.5249.126
> * 替换规则支持js,可以用js判断匹配到的内容决定替换为什么,匹配到的内容变量为result,替换为@js:开头则自动采用js判断替换内容
> * 书架管理添加筛选功能
> * 搜索支持搜索范围多分组和单书源设置
> * 书源管理界面书源菜单添加单书源搜索书籍功能
> * 复web阅读时app未退出阅读界面导致的进度bug by Xwite
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

