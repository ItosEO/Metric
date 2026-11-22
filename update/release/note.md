## 变更

> 建议更新，本次存在服务接口更新，后续会停止兼容

### 帧率记录
- 新增网络延迟/流量记录功能
- 优化控制中心磁贴记录时的稳定性

### 进程记录
- 新增导出为 JSON 功能

### 悬浮窗
- 调整缩放调节最大值到 150%

### 应用管理
- 优化 Dex2oat 配置 Sheet 样式
- 修复应用管理顶栏按钮的一些 bug

### 其他
- 清理冗余代码、废弃组件与无用资源
- 更新依赖，更好的模糊效果

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