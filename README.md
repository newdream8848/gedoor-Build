## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.081920.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.081920/legado-3.22.081920.apk) 上次构建时间:2022-08-19 20:28:42
<!--start-->
> **2022/08/19**
> 
> * 更新cronet: 104.0.5112.97
> * 现在选择文本朗读会从选择处一直往下朗读,朗读更方便
> * 阅读界面的TXT目录正则 弹框中也支持正则标题示例
> * 一些优化 by 821938089
> * 优化epub封面加载，修复图片读取，修复目录索引问题
> * 本地内容获取时尝试HTML实体解码，优化报错提示和添加日志
> * 优化书源校验，注释Error行
> * 订阅源、书架管理添加选中所选区间
> * 优化订阅源分组显示已启用分组，订阅源管理增加已启用、已禁用、需要登录、未分组分组
> * 订阅源长按菜单添加禁用源、分组管理排序
> * 添加返回时提示放入书架设置
> * 优化备份设置子文件夹对话框内容显示和校验
> * 修复搜索手动停止滑到底又重新搜索
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

