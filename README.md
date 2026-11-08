# Beautiful KernelSU Manager（美化版 UI 演示）

这是一个使用 **Jetpack Compose + Material 3** 重新设计的 KernelSU 管理器界面演示项目。

> **重要说明**  
> 本项目仅为 **UI 美化演示**，不包含真实的 KernelSU 内核通信、模块安装、超级用户授权等功能。  
> 如需真实可用的管理器，请使用官方 [KernelSU Manager](https://github.com/tiann/KernelSU) 或基于官方源码进行二次开发。

## 功能预览

- 首页状态卡片（KernelSU 状态 / 超级用户 / 模块）
- 模块列表（支持开关、更新角标）
- 超级用户列表（授权开关）
- 设置页
- 深色优先、大圆角、现代卡片式设计

## 如何打包成 APK

1. 用 **Android Studio**（推荐最新版）打开本项目根目录
2. 等待 Gradle 同步完成
3. 菜单栏选择 **Build → Build Bundle(s) / APK(s) → Build APK(s)**
4. 生成的 APK 位于：  
   `app/build/outputs/apk/debug/app-debug.apk`

也可以直接点击运行按钮安装到手机/模拟器查看效果。

## 环境要求

- Android Studio Ladybug 或更新版本
- JDK 17+
- minSdk 26

## 后续扩展建议

若要把此 UI 接到真实 KernelSU：

1. Fork 官方仓库 https://github.com/tiann/KernelSU
2. 将本项目的 `ui` 层代码迁移到官方 `manager` 模块
3. 替换假数据为官方的 `Natives` / ViewModel 数据源

祝使用愉快！

