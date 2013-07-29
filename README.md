# Seajs包含jQuery版本

Seajs的版本是2.0.0

jQuery的版本是1.10.1

在seajs里面直接调用即可，不需要额外引用jQuery

```
define(['jquery'], function($){
	console.log($().jquery); //1.10.1
});
```

__注意__

该源码内的jQuery对象不会暴露在全局内
