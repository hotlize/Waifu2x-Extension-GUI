# 更新日志
#### 历史版本下载:
#### 微云链接：https://share.weiyun.com/5abrs1W 密码：s4monw
---
## [v0.37-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.37-beta)
#### 更新日志:
- 新特性:自定义".jpg"文件压缩后的图像质量
- 完善浏览文件对话框的文件扩展名过滤
- 更新ImageMagick(7.0.9-22-Q16-x64)
- 提高稳定性
- 完善简体中文支持
- 其他小改进
- 修复bug:程序关闭后滞留后台
---
## [v0.35-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.35-beta)
#### 更新日志:
- 新特性:自定义全局字体大小(附加设置)
- 新特性:浏览与添加文件
- 性能优化
- 提高稳定性
- 审查代码,增加代码注释
- 界面布局调整
- 多处微小改进
- 修复bug:不能兼容Windows系统的自定义缩放
- 修复bug:某些特殊情况下无法正常识别文件是否被重复添加的问题
- 修复bug:无法保存降噪等级设置
---
## [v0.31-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.31-beta)
#### 更新日志:
- 新特性:加载文件列表时显示进度
- 新特性:可自定义"自定义分辨率"的纵横比策略(在[附加设置]内)
- 新特性:手动保存设置后弹窗提示
- 新特性:可以一直隐藏"设置"(可选,默认禁用,在[附加设置]内)
- 新特性:显示GIF和视频线程数量之总数
- 界面布局微调
- 修复bug:当正在处理gif时,停止处理进程后无法正常改变文件处理状态
---
## [v0.291-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.291-beta)
#### 更新日志:
- 新特性:关闭程序时自动保存设置(可选,默认启用)
- 新特性:可以一直隐藏"输入路径"(可选,默认禁用)
- 新特性:增加[关于]
- 新特性:权限检测
- 调整界面布局,将部分设置选项移动到[附加设置]内
- 完善简体中文支持
- 修复bug:一些特殊情况下程序会滞留在后台运行
---
## [v0.281-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.281-beta)
#### 更新日志:
- 新特性:[文件列表]支持选中后再次点击取消选中
- 界面美化
- 调整界面布局
- 完善简体中文支持
- 修复bug:某些情况下GIF的帧无法正常排列
- 修复bug:某些情况下线程会被提前自动关闭导致任务无法完成
- 修复bug:某些情况下程序无法完全退出会滞留在后台执行无限循环
- 修复bug:当系统内没有Java运行环境时,调用Anime4k可能会造成软件进入无限循环
---
## [v0.25-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.25-beta)
#### 更新日志:
- 新特性:首次启动时读取屏幕分辨率并设定为默认的自定义分辨率值
- 新特性:加载文件列表时,在Textbrowser内自动输出状态为[失败]的条目
- 更新FFmpeg(4.2.2)
- 修复bug:某些特殊的情况下,自动检查更新会误报存在新版本
- 修复bug:无法正常执行自动关闭计算机
- 修复bug:切换语言后无法正常显示[文件数量]
- 完善简体中文语言支持
---
## [v0.21-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.21-beta)
#### 更新日志:
- 新特性:进度条左侧显示[完成数量/总数量].
- 新特性:增加设置选项,控制是否在启动时自动检查更新.(不建议关闭自动更新)
- 新特性:文件列表下方显示总文件数量.
- 新特性:保存/读取文件列表
- 新特性:自动关机前自动保存文件列表,下次开机后可手动加载文件列表查看文件处理情况
- 新特性:自动关机前弹窗提示
- 完善简体中文语言支持
- 根据当前语言来选择要打开的说明文档
- 在开始处理一个文件前,先检查其是否存在
- 修复bug:保存设置后,无法正常读取曾保存的[图像风格]设置
- 修复bug:移除单一条目后,其余所有条目的自定义分辨率设置会被清除
- 修复bug:当文件列表内有文件名称相同而扩展名不同的文件时, 如果启用多线程会造成读写冲突.
- 修复bug:自动检测到新版本后无法正常打开新版下载页面的问题.
---
## [v0.12-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.12-beta)
#### 更新日志:
- 新增功能: 自动检查更新
- 修复bug: gif和视频无法正常获取放大倍数设定
- 修复bug: 当处理视频或gif时, 如果产生错误, 将导致线程管理问题.
---
## [v0.11-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.11-beta)
#### 更新日志:
- 新增功能: 自定义图片, GIF和视频输出时的分辨率. (应一名匿名捐赠者的要求.🧐)
- 新增功能: 多语言.(加入简体中文) 🎉🥳🎉(应一名匿名捐赠者的要求.🧐)
- 新增功能: 支持保存当前设置, 启动软件时自动恢复上一次保存的设置.
- 新增功能: 切换设置选项显示状态.(隐藏/显示)
- 新增功能: 切换[输入路径]显示状态.(隐藏/显示)
- 新增功能: 用户误操作时弹出提示.
- 新增功能: 更改Textbrowser的字体大小后自动滑动到底端.
- 新增功能: Textbrowser输出新内容后自动滑动到最底端
- 新增功能: 文件列表表格自动根据显示内容调整大小
- 新增功能: 检测可用GPU与设定GPU ID
- 改进tableview选中逻辑. 当其中一个tableview被选中时, 其余两个自动取消选中.
- 优化tableview显示逻辑, 在输入文件后, 仅改变对应tableview的显示状态.
- 去除冗余代码
- 修复bug: 当[Re-process finished files]未启用时, 尝试移除已经处理完成的文件会导致程序崩溃.
- 修复bug: [video_gif_info.exe] 无法正常读取中文字符
- 修复bug: 处理完所有文件后未自动启用[兼容性检测]按钮
---
## [v0.01-beta](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/tag/v0.01-beta)
#### 更新日志:
- 第一个发行版.
