# 字体与第三方许可索引

砚藏在应用内提供可离线查看的字体名称、版权声明与完整许可正文。安装后可从“设置 → 关于砚藏 → 字体与第三方许可”查看。

## MiSans

- 用途：砚藏界面字体
- 版权声明：Copyright © 2020-2025 Beijing Xiaomi Mobile Software Co.,Ltd. All Rights Reserved.
- 官方许可与来源：[MiSans 字体下载](https://hyperos.mi.com/font-download/)

## Noto Serif CJK SC

- 用途：可选阅读字体
- 版权声明：© 2017-2024 Adobe (http://www.adobe.com/).
- 许可：SIL Open Font License 1.1
- 官方许可来源：[Noto CJK Serif LICENSE](https://github.com/notofonts/noto-cjk/blob/main/Serif/LICENSE)

本索引用于帮助定位许可信息，不替代随 APK 提供的完整许可正文。字体许可只适用于对应字体，不表示砚藏应用源码公开，也不改变砚藏的使用边界。


## 聊天阅读运行时（0.2.4）

下列可信本地组件随APK提供，不从CDN加载。完整许可正文同时提供于本仓库；对应依赖许可不改变砚藏本身的使用边界。

| 组件 | 用途 | 许可正文 |
| --- | --- | --- |
| Marked 17.0.5 | Markdown解析 | [MIT](licenses/MARKED_LICENSE.txt) |
| DOMPurify 3.4.16（Cure53及贡献者） | HTML净化 | [Apache-2.0（采用此许可选项）](licenses/DOMPURIFY_LICENSE.txt) |
| parse5 8.0.1、entities 8.1.0 | HTML片段解析 | [MIT](licenses/HTML_PARSER_LICENSES.txt) |
| CSS Tree 3.2.1、source-map-js 1.2.2 | CSS解析／生成 | [MIT及BSD-3-Clause](licenses/CSS_PARSER_LICENSE.txt) |
| DOMPurify内嵌Babel辅助运行时（Facebook及贡献者） | 编译辅助 | [MIT](licenses/BABEL_RUNTIME_LICENSE.txt) |

esbuild 0.28.2仅用于本地构建，不作为运行时进入APK。APK内assets/webruntime1保留四份完整依赖许可；Babel辅助代码自身保留上游许可头，本仓库补充完整MIT许可正文。
