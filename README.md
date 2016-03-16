# A Chrome extends boilerplate

## 如何安装？

### 一、下载文件目录到任意位置：

	# 通过git命令下载
	$ git clone https://github.com/xiongwilee/chrome-extensions-boilerplate.git
	
	# [todo]或者通过npm安装
	$ npm install chrome-extensions-boilerplate

### 二、编译生成目标文件：

	# 到刚刚下载的目录
	$ cd chrome-extensions-boilerplate
	
	# npm install可能需要root权限,build生成的dist目录就是插件目录
	$ npm install && npm run build

### 三、本地开发

进入`chrome://extensions/`，勾选`开发者模式`，点击`加载已解压的扩展程序...`，选择刚刚编译的`chrome-extensions-boilerplate/dist`目录即可。

开发中可使用实时编译：

	npm run dev

## TODO

* livereload
* 生成sougou/360 浏览器插件boilerplate
* 详细的`manifest.json`说明文档
* 开发APP、主题boilerplate
* 开发插件资源连接
* 通过gulp生成crx文件
