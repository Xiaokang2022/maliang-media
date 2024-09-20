Changelog / 更新日志
===================

> [!TIP]  
> This changelog has the following 7 types of updates, each of which is represented by 7 different colors  
> 此更新日志有以下 7 中类型的更新内容，分别用 7 中不同颜色来表示
> 
> * 🟢 **Added / 新增**
> * 🔴 **Removed / 移除**
> * 🟡 **Changed / 变更**
> * 🔵 **Optimized / 优化**
> * 🟣 **Fixed / 修复**
> * 🟠 **Deprecated / 弃用**
> * 🟤 **Refactored / 重构**

🔖 `1.1.1`
-----------

🕓 *Release Date / 发布日期 : 2024-09-20*

🟣 **Fixed / 修复**

- Fixed some incorrect docstrings  
修复了部分错误的文档字符串

- Fixed a bug where clicking on the screen to pause the video would give an error when closing the bottom control bar  
修复了关闭底部控制栏时点击画面暂停视频会报错的 bug

- Fixed a bug where using the bottom control bar would result in an error when using a nested canvas  
修复了嵌套使用画布时使用底部控制栏会报错的 bug

🔖 `1.1.0`
-----------

🕓 *Release Date / 发布日期 : 2024-09-20*

🟤 **Refactored / 重构**

- The whole is refactored, and the specific API is shown in [Documentation](https://xiaokang2022.github.io/tkintertools-docs/3.0/documents/media/)  
整体全部重构，具体 API 见[文档](https://xiaokang2022.github.io/tkintertools-docs/3.0/documents/media/)

🔖 `1.0.6`
-----------

🕓 *Release Date / 发布日期 : 2024-09-16*

🟣 **Fixed / 修复**

- Fixed a bug where the video playback speed was abnormal  
修复了视频播放速度异常的 bug

🔴 **Removed / 移除**

- Removed the `interval` parameter for `VideoCanvas`  
移除了 `VideoCanvas` 的 `interval` 参数

🔖 `1.0.5`
-----------

🕓 *Release Date / 发布日期 : 2024-09-16*

🟢 **Added / 新增**

- Class `VideoCanvas` adds parameters `click_pause` and `auto_play`  
类 `VideoCanvas` 新增参数 `click_pause` 和 `auto_play`

🟡 **Changed / 变更**

- The parameter `max_fps` of the class `VideoCanvas` has been changed to `interval`  
类 `VideoCanvas` 的参数 `max_fps` 变更为 `interval`

🔵 **Optimized / 优化**

- Improved performance of `VideoCanvas`  
改善 `VideoCanvas` 的性能

🔖 `1.0.4`
-----------

🕓 *Release Date / 发布日期 : 2024-09-16*

🟤 **Refactored / 重构**

- Modified the syntax of some of the code to be compatible with Python 3.10  
修改部分代码的语法，以兼容 Python 3.10

🔖 `1.0.3`
-----------

🕓 *Release Date / 发布日期 : 2024-09-16*

🟢 **Added / 新增**

- Added a left-click function to pause  
新增了鼠标左键点击可以暂停的功能

- Added a function for the mouse wheel to adjust the volume  
新增了鼠标滚轮可以调节音量的功能

- Added the display of video playback progress information  
新增视频播放进度信息的显示

🟡 **Changed / 变更**

- Change the progress bar to a slider bar and you can drag the video progress  
将进度条更改为滑动条，可以拖动视频进度了

🟣 **Fixed / 修复**

- Fixed a bug where video playback would cause continuous stuttering  
修复了视频播放完成时会产生持续卡顿的 bug

🔵 **Optimized / 优化**

- Optimize the UI  
优化 UI

🔖 `1.0.2`
-----------

🕓 *Release Date / 发布日期 : 2024-09-16*

🟢 **Added / 新增**

- The `VideoCanvas` class adds the initialization parameter `control` to enable the built-in UI  
类 `VideoCanvas` 新增初始化参数 `control` 来开启内置的 UI

🟡 **Changed / 变更**

- Change the default value of the initialization parameter `max_fps` of the class `VideoCanvas` to 30  
修改类 `VideoCanvas` 的初始化参数 `max_fps` 的默认值到 30

- Change the default value of the initialization parameter `zoom_item` of the class `VideoCanvas` to `True`  
修改类 `VideoCanvas` 的初始化参数 `zoom_item` 的默认值到 `True`

🔖 `1.0.1`
-----------

🕓 *Release Date / 发布日期 : 2024-09-16*

🟢 **Added / 新增**

- The `VideoCanvas` class adds an initialization parameter `max_fps` to limit the maximum fps of the video  
类 `VideoCanvas` 新增初始化参数 `max_fps` 来限制视频的最大帧率

🔵 **Optimized / 优化**

- Greatly optimized performance and improved video stuttering  
极大地优化了性能，改善了视频卡顿的问题

🔖 `1.0.0`
-----------

🕓 *Release Date / 发布日期 : 2024-09-15*

🟢 **Added / 新增**

- A new class `VideoCanvas` has been added to meet the requirements for video playback  
新增类 `VideoCanvas` 来实现对视频播放的需求
