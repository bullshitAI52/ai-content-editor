# 本地第三方库说明

本目录包含应用所需的所有第三方JavaScript库的本地版本。

## 库列表

### 核心库
- **marked.min.js** - Markdown解析器
  - 版本: 9.1.6
  - 来源: https://cdn.jsdelivr.net/npm/marked@9.1.6/marked.min.js
  - 功能: 将Markdown文本转换为HTML

- **FileSaver.min.js** - 文件保存库
  - 版本: 2.0.5
  - 来源: https://cdn.jsdelivr.net/npm/file-saver@2.0.5/dist/FileSaver.min.js
  - 功能: 在浏览器中保存文件

- **purify.min.js** - HTML清理库
  - 版本: 3.0.8
  - 来源: https://cdn.jsdelivr.net/npm/dompurify@3.0.8/dist/purify.min.js
  - 功能: 清理和净化HTML内容，防止XSS攻击

### Excel处理库
- **xlsx.full.min.js** - Excel文件处理库
  - 版本: 0.18.5
  - 来源: https://cdn.jsdelivr.net/npm/xlsx@0.18.5/dist/xlsx.full.min.js
  - 功能: 读取、写入和操作Excel文件

### 数学公式库
- **tex-mml-chtml.js** - MathJax数学公式渲染库
  - 版本: 3.x
  - 来源: https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js
  - 功能: 渲染LaTeX数学公式

## 优势

1. **离线运行**: 无需网络连接即可使用所有功能
2. **加载速度**: 本地文件加载更快，减少网络延迟
3. **版本稳定**: 锁定特定版本，避免CDN更新导致的问题
4. **隐私保护**: 不依赖外部CDN，数据完全本地处理
5. **可靠性**: 避免CDN服务中断影响应用使用

## 更新说明

如需更新库版本，请：
1. 下载新版本到本目录
2. 更新版本号信息
3. 测试所有功能确保兼容性
4. 更新此README文件

## 文件大小

- marked.min.js: ~50KB
- FileSaver.min.js: ~15KB
- purify.min.js: ~45KB
- xlsx.full.min.js: ~1.2MB
- tex-mml-chtml.js: ~1.5MB

总计约3MB，相比在线版本具有更好的缓存性能。
