# Awesome Seewo

收集与希沃相关的第三方工具、定制、教程等资源。

本列表中不含 [HugoWidget](https://github.com/HugoWidget) 组织项目，访问 [简介](https://github.com/HugoWidget/HugoWidget) 以了解其他 HugoWidget 项目。

本列表不定时更新，已经停止开发/归档的项目仍会保留。

> [!CAUTION]
>
> 本列表收录的项目均为社区开发，与希沃官方无隶属关系，请遵守相关法律法规和软件许可。

## 目录

- [优化与管理](#优化与管理)
- [白板激活](#白板激活)
- [定制与美化](#定制与美化)
- [监控与反监控](#监控与反监控)
- [工具与辅助](#工具与辅助)
- [账号与登录](#账号与登录)
- [课件管理](#课件管理)
- [教程与指南](#教程与指南)
- [更多合集](#更多合集)

---

## 优化与管理

- **HugoAura 相关项目**

  希沃管家注入式优化方案，功能极其丰富，[主仓库](https://github.com/HugoAura/Seewo-HugoAura) 停止开发  
  当前活跃分支：[blingbling-bow](https://github.com/blingbling-bow/HugoAura-Enhanced)

- **SWToolkit 相关项目**

  **特点**：另一个独立的 C/C++ 希沃优化方案，使用便捷，相关资源暂未开放。  
  **许可证**：MIT

- [seewo_jailbreak](https://github.com/CatMe0w/seewo_jailbreak)

  **技术栈**：C / Python  
  **功能**：通过修补希沃管家 `bind_zmodule.dll`，绕过密码验证。  
  **特点**：无需破解密码，直接修改验证逻辑。  
  **许可证**：MIT

- [bruteforce_passwordv3](https://github.com/CatMe0w/bruteforce_passwordv3)

  **技术栈**：C / Python  
  **功能**：获取希沃 PASSWORDV3 / LockPasswordV3 管理员与锁屏密码。  
  **特点**：适用于 V3 算法。  
  **许可证**：MIT

- [Seewo_Assistant_Password_Recovery_Tool_V2](https://github.com/zhy8388608/Seewo_Assistant_Password_Recovery_Tool_V2)

  **技术栈**：Web、Python  
  **功能**：V2 希沃管家密码计算工具。  
  **特点**：支持本地密码和激活码 V2 版本的相关操作。  
  **许可证**：无

- [Seewo-Activation-Code-Calculator](https://github.com/f4bb0/Seewo-Activation-Code-Calculator)

  **技术栈**：JavaScript  
  **功能**：V2 激活码扫描/计算工具，用于生成或解析希沃锁屏激活码。  
  **特点**：支持激活码 V2 版本的解析与生成。  
  **许可证**：Apache-2.0

- [SeewoActivationTool](https://github.com/la-1314/SeewoActivationTool)

  **技术栈**：Kotlin  
  **功能**：扫码或从相册识别希沃锁屏二维码，解析参数并计算 V2 激活码。  
  **特点**：Android 端工具。  
  **许可证**：未知

- [seewo-obstructor](https://github.com/std-external/seewo-obstructor)

  **技术栈**：C++（DLL 注入）  
  **功能**：数据提取、上报拦截伪造、截图/摄像头拦截、解除冰点还原等。  
  **特点**：可读取明文数据，但某些操作可能导致崩溃；可用但稳定性一般。  
  **许可证**：AGPL-3.0

- [swfrztool](https://github.com/XSere/swfrztool)

  **技术栈**：C（运行时内存篡改 + 内核执行流劫持）  
  **功能**：即时解除冰点还原保护、模拟冰点保护状态、白名单扇区控制等。  
  **特点**：动态解除冰点；仅适用于 Win10 x64 以上环境。  
  **许可证**：AGPL-3.0

## 白板激活

- [sw_en3_keygen](https://github.com/LIGHTENINGXGAMES/sw_en3_keygen)

  **技术栈**：Go  
  **功能**：为希沃 EasiNote3 生成激活文件 `SWAF1501.swaf`。  
  **特点**：仅供教育用途，激活旧版以保留高级功能。  
  **许可证**：未知

- [EN3Cracker](https://github.com/HuskeyDev/EN3Cracker)

  **技术栈**：C#  
  **功能**：解除希沃白板 3 试用期限制，恢复手写识别等功能。  
  **特点**：针对官方关闭激活服务器的情况，通过修改二进制实现永久激活。  
  **许可证**：MIT

- [EasiNote-5-Crack-Tool](https://github.com/YXC-Lhy/EasiNote-5-Crack-Tool)

  **技术栈**：C#  
  **功能**：激活希沃白板 5 至专业版，创建免登录打开白板的快捷方式，修改启动画面。  
  **特点**：简单激活工具，需在激活前彻底关闭希沃白板。  
  **许可证**：未知

- [TruthEasiNote5](https://github.com/yux112/TruthEasiNote5)

  **技术栈**：C#（.NET Framework）  
  **功能**：使非希沃一体机也能模拟希沃品牌一体机的启动过程。  
  **特点**：修补希沃白板5的配置文件，使用命名管道结束相关进程，启动服务与白板。  
  **许可证**：MIT

## 定制与美化

- [Seewo-Custom_Start](https://github.com/SRInternet-Studio/Seewo-Custom_Start)

  **技术栈**：Visual Basic .NET  
  **功能**：自定义希沃启动器，可将任何软件与希沃白板联动启动，替代默认启动页面。  
  **特点**：解决手动替换启动页的混乱，提供统一启动入口。  
  **许可证**：未知

- [custom-seewo-splash-screen](https://github.com/fengyec2/custom-seewo-splash-screen)

  **技术栈**：Python 3.8+、PyQt6等  
  **功能**：图形化替换希沃白板 / WPS Office 启动图：预设图片、备份/还原、防止恢复。  
  **特点**：Fluent UI 设计，支持 Windows/Linux。  
  **许可证**：GPL-3.0

## 监控与反监控

- [SeewoMonitor](https://github.com/Mistveil-Z/SeewoMonitor)

  **技术栈**：C# (.NET)、ClassIsland Uri、系统通知  
  **功能**：检测希沃集控的监控行为，当教师发起远程桌面时，发送提醒。  
  **特点**：支持自定义检测间隔、日志输出；可与 ClassIsland 自动化集成。  
  **许可证**：GPL-3.0

- [SeewoServantLite](https://github.com/fengyec2/SeewoServantLite)

  **技术栈**：Python 3.9+、win32gui、websockets  
  **功能**：实时监控火绒安全弹窗，通过 Websocket 向安卓客户端发送告警，检测摄像头使用。  
  **特点**：依赖火绒的隐私保护弹窗作为检测信号。  
  **许可证**：GPL-3.0

- [NoMoreMonitor](https://github.com/lilith-is-all-you-need/NoMoreMonitor)

  **技术栈**：C、MinHook、DLL 注入  
  **功能**：Hook 希沃相关进程的 `media_framework_device.dll` 函数，拦截摄像头请求并通知用户。  
  **特点**：底层拦截，同时支持 DirectShow 和 Media Foundation；纯本地运行，无网络请求。  
  **许可证**：MIT

- [StarReminder](https://github.com/Vistaminc/StarReminder)

  **技术栈**：C# (.NET 8, WPF)  
  **功能**：监控摄像头/麦克风使用，提供 Defender 风格通知、Toast、持续水印提醒。  
  **特点**：从设备层面检测，现代化 WPF 界面。  
  **许可证**：MIT

## 工具与辅助

- [SeewoPenTweaker](https://github.com/hxabcd/SeewoPenTweaker)

  **技术栈**：C++、原生 Win32 API  
  **功能**：响应希沃翻页笔 AI 键的 Ctrl+Shift+Alt+P/Q 组合，模拟鼠标操作，可配置延时。  
  **特点**：低体积、低占用、启动快。  
  **许可证**：未知

- [SeewoPan](https://github.com/PANDAJSR/SeewoPan)

  **技术栈**：Flutter、Node.js  
  **功能**：希沃品课云盘第三方客户端，支持文件管理、上传下载队列、文件预览、分享链接。  
  **特点**：可挂载为系统 WebDAV 目录；包含命令行工具用于自动化。  
  **许可证**：GPL-3.0

- [Seewo-DesktopAnnotation-Replacement](https://github.com/EmerMine/Seewo-DesktopAnnotation-Replacement)

  **技术栈**：Python、PySide6  
  **功能**：将希沃桌面 2.0+ 自带的桌面批注程序替换为第三方批注软件。  
  **特点**：直接替换批注文件，提供参数用于设置和调试。  
  **许可证**：GPL-3.0

## 账号与登录

- [SeewoAutoLogin（独立版）](https://github.com/Pro-Qin/SeewoAutoLogin)

  **技术栈**：C# (.NET 8, WPF)、WebView2等  
  **功能**：多希沃账号管理，本地 SSO 网关，账号列表轮换，自动刷新令牌，密码保护，托盘常驻。  
  **特点**：独立安装包；数据使用 DPAPI 加密。  
  **许可证**：GPL-3.0

- [SeewoAutoLogin（ICC-CE 插件版）](https://github.com/CJKmkp/SeewoAutoLogin)

  **技术栈**：C# (.NET 6)、ICC-CE 插件 SDK  
  **功能**：在 ICC-CE 插件中管理希沃账号，支持密码/扫码登录，本地 SSO 网关，用户列表轮换。  
  **特点**：专为 ICC-CE 设计，安装为 `.icpx` 包；配置存储于插件目录，令牌本地加密。  
  **许可证**：GPL-3.0

- [ENAL-rs](https://github.com/xiaofeiTM233/ENAL)

  **技术栈**：Rust、Axum、Tokio、AES-256-GCM、Next.js 16  
  **功能**：希沃账号管理与 SSO 代理服务，支持账密/扫码/令牌登录，自动续期令牌。  
  **特点**：跨平台（Win/Linux/macOS），单文件静默运行，数据不落明文。  
  **许可证**：自定义

- [EasiAuto](https://github.com/hxabcd/EasiAuto)

  **技术栈**：Python、PySide6  
  **功能**：自动登录希沃白板，支持四种登录方案，可配合 ClassIsland 实现定时自动登录。  
  **特点**：界面友好，配置简单；推荐与 ClassIsland 联动实现全自动登录。  
  **许可证**：GPL-3.0

## 课件管理

- [ENAnalyzer](https://github.com/howdy213/ENAnalyzer)

  **技术栈**：Python、wxPython  
  **功能**：希沃白板课件自动打包，扫描本地数据目录、自动转存、缓存清理、禁用部分白板功能。  
  **特点**：支持按账户分文件夹输出，后台静默运行（系统托盘）。  
  **许可证**：GPL-3.0

## 教程与指南

- [seewo-tutorial-web](https://github.com/seewo-geek/seewo-tutorial-web)

  **技术栈**：Web  
  **功能**：电教委入门指南网页版，面向学校电教管理员的希沃设备使用与维护教程。  
  **特点**：由“希沃售后业绩冲击部”维护，电教委入门指南网站的源码仓库。  
  **许可证**：CC BY-NC-SA 4.0

## 更多合集

这些并非希沃工具合集，而是可用于一体机的辅助工具清单，一并收录：

- [智教联盟辅助工具收集帖](https://forum.smart-teach.cn/d/2692-lun-tan-suo-you-fu-zhu-gong-ju-shou-ji-yu-cha-xun-tie)
- [智教联盟站内辅助工具索引](https://blog.edicdn.eu.org/posts/smart-teach-tools.html)
- [Awesome IWB - 交互式白板软件合集](https://aiwb.smart-teach.cn/)
- [Awesome IWB - GitHub 项目版本](https://github.com/Awesome-Iwb/Awesome-Iwb)

---

## 贡献

欢迎提交 Pull Request 添加更多项目，或补充介绍。请确保项目与希沃相关，并附上简要说明。

## 许可证

本列表采用 [CC0 1.0 通用](LICENSE) 许可。
