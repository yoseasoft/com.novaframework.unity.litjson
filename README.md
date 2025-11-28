## NovaFramework - Unity 工程插件

NovaFramework的Litjson插件，提供Json操作相关的功能接口。

## 简介

这里没有使用原生的[LitJson](https://github.com/LitJSON/litjson)库，
而是使用了[LitJson4Unity](https://github.com/XINCGer/LitJson4Unity)，
因为它基于原生库上做了一些增强，具体增强功能可以参考其仓库说明。

## 使用文档

## 注意事项

使用方式(任选其一)

1. 直接在 `manifest.json` 的文件中的 `dependencies` 节点下添加以下内容：
    ```json
        {"com.novaframework.unity.litjson": "https://github.com/yoseasoft/com.novaframework.unity.litjson.git"}
    ```

2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：
https://github.com/yoseasoft/com.novaframework.unity.litjson.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下，会自动加载识别。
