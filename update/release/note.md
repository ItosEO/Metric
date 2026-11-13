## 变更

> 建议更新，本次存在服务接口更新，后续会停止兼容

### 帧率记录
- 修复帧率图表开头的缺失
- 修复大量记录下云备份与恢复出现的软件崩溃
- 优化进入帧率记录页面的流畅度
- 优化系统功能记录的提示弹窗文本
- 优化帧率记录删除按钮的样式
- 新增荣耀风扇状态记录

### UI 设计
- 移除 CheckBox 的点击涟漪
- 调整部分图标

### 应用管理
- 修复 SharedPreferences 设置时组件闪烁

### 刷新率管理
- 新增屏幕上显示刷新率开关
- 新增解除刷新率锁定
- 新增控制中心显示刷新率磁贴

### 其他
- 移除 Trace 采集
- 调整 ColorOS 无障碍警告弹窗的配置，改为默认关闭，预计一周内加入官方白名单（建议关闭此选项）
- 新增记录开始/结束时执行自定义脚本
- 新增 Perfetto 可视化脚本生成器
- 新增用户协议与隐私政策

---

## Changes

> Update recommended; this release includes service interface updates, and backward compatibility will be discontinued in the future.

### Frame Rate Recording
- Fixed the missing beginning of the frame rate chart
- Fixed software crashes during cloud backup and restore with large numbers of records
- Optimized the smoothness of entering the frame rate recording page
- Optimized the prompt popup text for system feature recording
- Optimized the style of the frame rate recording delete button
- Added Honor fan status recording
### UI Design
- Removed the click ripple of CheckBox
- Adjusted some icons
### App Management
- Fixed component flickering when setting SharedPreferences
### Refresh Rate Management
- Added a switch to display the refresh rate on the screen
- Added unlocking of the refresh rate lock
- Added a control center tile to display the refresh rate
### Other
- Removed Trace collection
- Adjusted the configuration of the ColorOS accessibility warning popup, changed to disabled by default, expected to be added to the official whitelist within a week (it is recommended to turn off this option)
- Added execution of custom scripts at the start/end of recording
- Added a Perfetto visualization script generator
- Added user agreement and privacy policy