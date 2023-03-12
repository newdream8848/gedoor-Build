## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.23.031210.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.23.031210/legado-3.23.031210.apk) 上次构建时间:2023-03-12 14:15:25
<!--start-->
> **2023/03/11**
> * 远程书籍添加webDav多配置
> * 更新文件类书源详情页界面逻辑
> * 尝试修复语音朗读
> * 修复特定情况下书籍导入界面计数错误
> * 修复阅读界面导航栏更新不及时
> * 修复某些以空白开头的链接的拼接
> * 修复某些空白备份恢复的错误弹窗
> * 修复章节都在一个xhtml里面的epub的内容解析
> * 修复某些epub文件里不规范html文档的解析
> * 本地备份也采用压缩包,和webDav备份保持一致,从webDav下载的备份文件不需要解压可以直接恢复
> * 本地书籍和远程书籍界面添加筛选功能
> * 其中一些更新由 Horis 和 Xwite 提供
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

