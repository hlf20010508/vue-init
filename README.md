# vue-init
本脚本用于快速初始化vue-cli2.0，自动增加axios、element-ui，更改默认host为0.0.0.0，删除自带的多余文件并可设置配合类flask后端自动导入打包后的文件

需要expect、vue-cli
<br/>

运行脚本，在当前目录下创建vue-cli2.0项目
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/hlf20010508/vue-init/master/vue-init.sh)"
```

<br/>

可编译生成成二进制文件vue-init，需要shc
```
bash compile.sh
```

<br/>

本脚本完全按照作者个人的使用习惯进行编写

<br/>

本脚本会在运行时自动将所有依赖安装好，包括axios、element-ui

可编辑main_code以及两行npm install代码来选择性安装

<br/>

自动导入打包文件到后端功能仅支持类flask框架，如flask、sanic，带有templates文件夹和static文件夹

无法兼容其他种类后端框架

可自行更改build_code以兼容其他框架
