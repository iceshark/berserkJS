# berserkJS（大名：狂暴JS  昵称：疯子JS）


页面性能分析与测试自动化工具，可用 JS 编写自己的检测、分析规则，并自动执行。

基于 QT 开发，理论上可以跨平台使用，前提是在目标平台编译并部署 QT 运行环境。

此工具用于尝试前端自动化分析页面网络请求数据，可以使用 JS 操作页面导向，获取所需数据。


#使用案例
=========
- 无界面浏览器测试：在不依赖本地任何浏览器的情况下，运行测试框架，如 QUnit，Capybara, QUnit, Mocha, WebDriver, YUI Test, BusterJS, FuncUnit, Robot Framework 等。
- 页面自动化：可以无障碍访问和操作网页的标准 DOM API 以及页面所用 JS 变量、对象、属性等内容。
- 屏幕捕获：以编程方式获取网页全部或部分内容，可根据 Selector 截取指定 DOM 元素渲染情况；包括 CSS，SVG 和 Canvas。可将截取图片 base64 化，以便发送给远端服务器保存。
- 网络监控：自动化的网络性能监控，跟踪页面所有资源加载情况并可简便的将输出结果格式化为标准HAR格式。
- 页面性能监控：自动化的页面渲染监控和 CPU、 内存使用情况监控，根据页面整体情况可简便的输出首次渲染时间、首屏渲染时间等关键数据。


#工具特性
=========
- 跨平台性：基于 Qt 开发，可跨平台编译，部署。内置基于 QtWebkit 的浏览器环境。源码需在目标系统中编译后，可产生运行于 Windows / Linux / Mac 系统的可执行文件。
- 功能性：工具内置 webkit 浏览器内核，可响应浏览器内核事件回调、支持发送鼠标消息给浏览器、包装浏览器网络请求数据为JS数据格式、可与浏览器内JS做数据交互。
- 开放性：工具将主要操作均包装为JS语法与数据格式，采用JS语法包装，前端工程师可根据API组装出符合各自预期的检测功能。
- 接口性：工具本身支持命令行参数，可带参调用。API支持处理外部进程读取输出流、支持HTTP发送数据。可由 WEB 程序远程调用后获取测试的返回结果。
- 标准性：完全真实的浏览器环境内 DOM，CSS，JavaScript，Canvas，SVG 可供使用，绝无无仿真模拟。
- 调试便利性: 具有 GUI 界面与命令行状态两种形式，开发调试期可使用 GUI 模式定位问题，实际运行时可开启命令行状态避免自动执行时 GUI 界面干扰。

API 页面
=========
- 详情请看文档页：
http://tapir-dream.github.com/berserkJS

介绍PPT
=========
- 下载地址：http://t.cn/zWcKani