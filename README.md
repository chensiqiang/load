load.js 动态载入css和js文件，简单方便，适合模块化设计。
说明：https://ruchu.me/single/ew0uzmcg7n.html

动态载入js文件
```
load('file.js');
```


动态载入css文件
```
load('file.css');
```


动态载入多个文件
```
load(['file1.css','file.js']);
```


载入文件并回调函数
```
load('file1.js',function(){
    //执行代码
});
```

```
load(['file1.js','file2.js','file3.js'],function(){
    //执行代码
});
```


载入上一级文件
```
load(['../file1.js','file2.js','file3.js'],function(){
    //执行代码
});
```
