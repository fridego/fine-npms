##### rimraf 是什么

nodejs上的rm-rf命令行工具（[递归]删除文件以及文件夹）

##### rimraf的使用方法

* 安装npm

```
npm install rimraf
```
* 使用方法

```
const rm = require('rimraf');
// 递归删除当前目录下的rm文件
rm('./rm', function(err){ // rm 为目录
    if(err){
        throw err;                   
    }
})
```

##### [rimraf源码分析](./source.md)
