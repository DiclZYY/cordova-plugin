# 百度移动统计Cordova插件

## How to debug:
1. clone this project
2. remove the old plugin from the project
  ```
  cordova plugin remove cordova-plugin-baidumobstat
  ```

3. add the plugin

  	```
  	cordova plugin add cordova-plugin-baidumobstat
  	```

4. config
	
	参考cordova-sample部分

4. build and debug
	
	```
	cordova build
	cordova run android  (cordova run ios)
	```

## 2019.11.8
## Features

将配置项全部放置到plugin.xml中，免去每次安装都要重新拷贝文件和添加AndroidManifest.xml配置的麻烦

### iOS Quirks

Download the file `libBaiduMobStat.a` which is too big had been ignored by .ignore. So you have to download it and place it in `lib\ios` directory.

After test some times, the file `libBaiduMobStat.a` rename to `BaiduMobStat.a` is required.