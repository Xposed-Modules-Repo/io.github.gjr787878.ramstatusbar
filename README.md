# RamStatusBar

在状态栏时钟位置显示实时内存占用的 LSPosed 模块。

## 功能特性

- 三种显示模式：仅时间 / 时间+内存 / 仅内存，1秒内生效，无需重启
- 点击时钟查看 CPU/GPU：循环查看 CPU/GPU 占用率与温度，10秒自动恢复
- 自定义背景颜色：HSV 取色盘 + 亮度/透明度调节 + 预设色板，支持完全透明
- 深度休眠统计

## 安装

1. 下载并安装 APK
2. LSPosed 管理器 → 模块 → 启用 RamStatusBar
3. 作用域勾选 `com.android.systemui`
4. 重启手机（首次安装必须）
5. 打开 RamStatusBar → 配置页 → 选择显示模式 → 授予 Root 权限

## 要求

- Android 8.0+ (API 26+)
- Root
- LSPosed / LSPosed_mod
- 作用域：`com.android.systemui`

## 注意

- 仅用于个人使用和学习交流
- 需要 Root + LSPosed，无 Root 无法使用
- 部分高度定制的 ROM 可能存在兼容性问题
- 排查问题：LSPosed → 日志 → 搜索「RamStatusBar」
- 
