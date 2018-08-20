# weapp-fontawesome-component
微信小程序的fa模块，项目使用 fa 的 4.x 版本

# 安装说明

1. 将 src/components 中的文件复制到项目中的 components 路径下.

# 加载说明

1. 在需要引入的 页面（Page） 或者 模块（Components） 中引入这个模块
    1. 编辑页面/模块中的 json 文件
    1. 在 json 文件中添加如下内容
    ```json
    {
      ...
      "usingComponents": {
        ...
        "fa": "../<PATH_TO_YOUR_COMPONENT_ROOT>/includes/fa/index",
        ...
      }
      ...
    }
    ```

# 用法
基本用法和fa 用法类似，下面列出一些用法是之前项目开发时候用到的，确认可以使用，其他用法请自行测试。

### 基本图标
在 wxml 中使用 fa 标签：Example：
```xml
<fa icon="fa fa-home"></fa>
```    

### 大图标
```xml
<fa icon="fa fa-home fa-lg"></fa> fa-lg
<fa icon="fa fa-home fa-2x"></fa> fa-2x
<fa icon="fa fa-home fa-3x"></fa> fa-3x
<fa icon="fa fa-home fa-4x"></fa> fa-4x
<fa icon="fa fa-home fa-5x"></fa> fa-5x
```  

### 堆叠图标
```xml
<fa icon="fa-stack fa-lg">
    <fa icon="fa fa-user-o fa-stack-1x"></fa>
    <fa icon="fa fa-circle-thin fa-2x fa-stack-2x"></fa>
</fa>
```
### 图标颜色

组件集成了一些bootstrap 4 的默认颜色，可以直接调用
```xml
<fa icon="fa fa-ban text-danger"></fa>
```

# 参考来源

[80percent/wechat-weapp-font-awesome](https://github.com/80percent/wechat-weapp-font-awesome)

[southyou/wxcss-fontawesome](https://github.com/southyou/wxcss-fontawesome)

