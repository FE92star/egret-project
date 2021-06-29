# Egret-基于白鹭引擎的H5小游戏项目

## 工程目录结构

```
|-- EgretProjects
    |-- README.md               
    |-- egretProperties.json    # 项目配置文件，包含引擎的版本和引擎库的配置
    |-- favicon.ico             # icon
    |-- index.html              # 入口文件
    |-- manifest.json           # 清单的json文件
    |-- package.json
    |-- tsconfig.json           # ts编译配置项，egret引擎编译时会读取这里的配置
    |-- wingProperties.json     # 资源配置json
    |-- .wing                   # 动画编辑器开发相关配置json
    |   |-- launch.json
    |   |-- settings.json
    |   |-- tasks.json
    |-- bin-debug               # 项目构建之后输出源码的目标文件夹
    |-- libs                    # 用于存放第三方库的源码
    |   |-- modules             # 核心引擎库安装在本地的目录位置
    |-- resource                # 资源
    |   |-- default.res.json    # 静态资源(图片等)对应的配置映射关系
    |   |-- default.thm.json    # eui组件皮肤和exml对应的配置项
    |   |-- assets              # 图片静态资源存放位置
    |   |-- config
    |   |   |-- description.json
    |   |-- eui_skins           # eui-skins对应的exml文件
    |-- scripts                 # 编译/构建脚本
    |-- src                     # 项目核心代码目录
    |   |-- AssetAdapter.ts
    |   |-- LoadingUI.ts
    |   |-- Main.ts
    |   |-- Platform.ts
    |   |-- ThemeAdapter.ts
    |-- template                # 项目编译的html模板
        |-- web
            |-- index.html
```
