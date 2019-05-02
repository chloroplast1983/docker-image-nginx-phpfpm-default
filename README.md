# nginx-vue

## 概述

项目内部使用针对`vue`框架的部署版本. 主要是路由进行了修改. 其他配置文件参见[nginx-front](https://github.com/chloroplast1983/docker-image-nginx-front)环境的配置文件.

主要修改如下:

* 默认`\`即`index`用`php`进行渲染.
* `xxx.com/api/xxx`这样的路由统一路由到`php`文件进行处理.

## 版本

这里所有版本都会链接到`nginx-front`中, 所以可能该项目版本号会和`nginx-front`的版本号不一致. 如果更新有不同的地方, 会单独罗列文件.

* [1.0](https://github.com/chloroplast1983/docker-image-nginx-front/blob/master/Docs/1.2.md)