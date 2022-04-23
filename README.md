## legado阅读3.0自动构建[![Android CI](https://github.com/10bits/gedoor-Build/workflows/Android%20CI/badge.svg)](https://github.com/10bits/gedoor-Build/actions)

> 默认从最新发布的tag构建,每次构建会自动清空18PlusList.txt

> 最新构建下载:[legado-3.22.042323.apk](https://github.com/newdream8848/gedoor-Build/releases/download/legado-3.22.042323/legado-3.22.042323.apk) 上次构建时间:2022-04-24 02:16:27
<!--start-->
> **2022/04/23**
> 
> * 修复js问题
> * 音频界面显示缓冲进度 by ag2s
> * 修复图片文字缓存bug
> * 修复在线朗读bug
> * 修复mlns epub目录识别失败
> 
> **2022/04/22**
> 
> * 键盘辅助配置加入备份恢复文件
> * 修复源管理界面添加删除分组不及时显示的bug
> * 修复其它一些bug
> * 更新js库
> 
> ```
> 实现 ES6 Object.values Object.entries Object.fromEntries
> 实现 ES2017 Object.getOwnPropertyDescriptors
> 添加：支持“catch”中的可选变量绑定
> 添加：反单引号里`${}`语法支持（用于字符串连接）
> 添加：equals (==) 等号的支持
> 添加：NativeArray.subList()
> 添加：Object.hasOwn
> 修复：（for of）导出字符串 of前无空格导致语法错误问题
> 其他一些优化
> ```
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

