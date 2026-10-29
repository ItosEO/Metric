## 变更

> 本次更新带来了大量改进，强烈建议更新

### 帧率监测与记录
- 新增筛选过滤帧率记录中的 加载、转场、菜单 等场景
- 新增帧率记录未过滤时的提示文本
- 重新加入帧率记录的小数点
- 优化帧率获取算法，提高数据准确性
- 修复荣耀 WIN/WIN RT2 帧率作弊导致的帧率采样异常问题
- 修复记录较短的情况下，帧率记录开头帧率为空

### 设备监测与调控
- 新增负载监视器显示 CPU 调速器
- 优化 zram 节点选择规则
- 优化 8Gen5 平台线程分配策略
- 优化 8Elite/8Gen5 的 CFM 线程分配策略
- 优化高压力下免 Root 读取 GPU 失效
- 移除规范化 CPU Usage 开关，现仅在记录中使用

### 悬浮窗
- 新增更方便的悬浮窗管理器入口（COUI）
- 新增悬浮窗的点触光效
- 新增悬浮窗缩放调节
- 新增开启多个悬浮窗时的警告提示
- 优化线程监视器样式
- 优化温度监视器样式
- 优化负载监视器样式
- 优化悬浮窗控制面板样式
- 优化悬浮窗流光轮廓效果
- 优化悬浮窗拖拽范围
- 修复悬浮窗拖拽超出边界后位移行程异常
- 适配悬浮窗 G2 圆角
- 调整帧率悬浮窗曲线改为 120 点
- 调整负载监视器为双击关闭

### UI 与交互
- 新增 COUI 17 风格组件，流光轮廓、弹性设计（建议在主题设置中调整）
- 新增 COUI 顶栏按钮
- 新增主页快速进入进程管理搜索（COUI）
- 重构模糊背景采样逻辑
- 重构 UI 组件框架
- 优化 Material 底栏样式
- 优化 LiquidGlass 底栏样式
- 优化菜单交互效果
- 优化纯色模式
- 优化多选框样式
- 优化开关样式
- 优化顶栏返回按钮可读性
- 优化顶栏渐进模糊采样，更细腻自然
- 优化 COUI 下的流畅度（Android 15 以上）
- 修复 Material 搜索框底部显示不完整的问题

### 功能与兼容性
- 新增 Shizuku 激活服务
- 新增 OriginOS 专属功能
- 重构电池信息校准，加入自动校准
- 调整部分页面从性能调控至更多功能

### 设置与其他
- 新增用户体验改进计划
- 优化日志级别选择界面
- 优化一些内部实现
- 修复应用管理菜单设置未持久化
- 移除 Disable 日志级别

> 我们可能在不久的将来停止对 Android12/12.1 的支持

---

## Changes

> This update brings a large number of improvements. Updating is strongly recommended.

### FPS Monitoring & Recording
- Added filtering for loading, transitions, menus, and other scenarios in FPS recordings
- Added a notice when FPS recording filters are not applied
- Restored decimal precision in FPS recordings
- Improved the FPS sampling algorithm for greater accuracy
- Fixed abnormal FPS sampling caused by FPS spoofing on HONOR WIN / WIN RT 2
- Fixed missing FPS data at the beginning of short recordings

### Device Monitoring & Tuning
- Added CPU governor information to the Load Monitor
- Optimized ZRAM node selection rules
- Optimized thread allocation for Snapdragon 8 Gen 5
- Optimized CFM thread allocation for Snapdragon 8 Elite / 8 Gen 5
- Improved GPU data reading without Root access under high system load
- Removed the Normalize CPU Usage toggle; normalization is now used only in recordings

### Floating Windows
- Added a more convenient entry point to the Floating Window Manager (COUI)
- Added touch lighting effects to floating windows
- Added floating window scaling controls
- Added a warning when multiple floating windows are enabled
- Improved the Thread Monitor UI
- Improved the Temperature Monitor UI
- Improved the Load Monitor UI
- Improved the floating window control panel UI
- Improved the glowing outline effect on floating windows
- Optimized floating window dragging boundaries
- Fixed abnormal dragging behavior after a floating window moves beyond screen boundaries
- Added G2 rounded corner support for floating windows
- Increased the FPS floating window graph to 120 data points
- Changed the Load Monitor to close on double-tap

### UI & Interaction
- Added COUI 17-style components with glowing outlines and elastic design (recommended to configure in Theme Settings)
- Added COUI-style top bar buttons
- Added quick access to Process Manager search from the home screen (COUI)
- Refactored background blur sampling logic
- Refactored the UI component framework
- Improved the Material bottom navigation bar
- Improved the LiquidGlass bottom navigation bar
- Improved menu interactions
- Improved Solid Color Mode
- Improved checkbox styles
- Improved switch styles
- Improved top bar back button visibility
- Refined progressive blur sampling in the top bar for smoother, more natural effects
- Improved UI smoothness on COUI (Android 15 and above)
- Fixed the Material search bar being cut off at the bottom

### Features & Compatibility
- Added Shizuku service activation
- Added OriginOS-exclusive features
- Refactored battery information calibration with automatic calibration support
- Moved some pages from Performance Tuning to More Features

### Settings & Other
- Added the User Experience Improvement Program
- Improved the log level selection interface
- Optimized various internal implementations
- Fixed App Manager menu settings not being saved persistently
- Removed the Disable log level

> We may stop supporting Android 12/12.1 in the near future.