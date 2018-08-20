# weapp-fontawesome-component
微信小程序的fa模块

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
        "fa": "../../components/partials/fa/index",
        ...
      }
      ...
    }
    ```

# 用法

在 wxml 中使用 fa 标签：Example：
```xml
<fa icon="fa fa-home"<fa
```    


dfs