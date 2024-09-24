# OneSlide —— 极简 Markdown PPT

OneSlide 是一个基于 Markdown 的极简幻灯片制作工具，适用于快速创建美观的演示文稿。

## 特点

- **简洁易用**：支持 Markdown 格式，方便快捷地编写幻灯片内容。
- **主题多样**：内置多种主题风格，轻松切换。
- **实时预览**：编辑内容后即时预览效果。
- **图片上传**：支持直接上传图片到幻灯片中。
- **PDF 导出**：一键导出为 PDF 文件。
- **演讲者模式**：开启演讲者模式，查看演讲备注。

## 快速开始

1. **安装依赖**

   - 确保已安装 Node.js 及 npm。
   - 运行 `npm install` 安装项目依赖。

2. **启动本地服务器**

   - 在项目根目录下运行 `npm start` 启动本地开发服务器。
   - 访问 `http://localhost:8080` 查看幻灯片编辑器。

3. **编辑幻灯片**

   - 使用 Markdown 语法编写幻灯片内容。
   - 上传图片并调整布局。
   - 选择合适的主题和转场效果。

4. **导出为 PDF**

   - 点击“下载 PDF”按钮，将幻灯片导出为 PDF 文件。

5. **开启演讲者模式**
   - 按 `S` 键进入演讲者模式，查看每张幻灯片的备注信息。

## 配置选项

- **主题选择**：通过点击“主题与特效”选项卡，选择不同的主题风格。
- **转场效果**：设置幻灯片之间的过渡效果，如滑动、淡化等。
- **对齐方式**：调整幻灯片内容的对齐方式，如居中、左上等。

## 技术栈

- **HTML**: 结构化页面布局。
- **CSS**: 样式美化及主题切换。
- **JavaScript**: 动态交互逻辑处理。
- **Markdown**: 内容编辑格式。

## 示例

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- 元数据及样式链接 -->
  </head>
  <body>
    <div class="control">
      <span class="iconfont icon-setting"></span>
    </div>
    <div class="menu">
      <!-- 编辑、主题、下载、演讲者模式等选项 -->
    </div>
    <div class="reveal">
      <div class="slides">
        <!-- 幻灯片内容区域 -->
      </div>
    </div>
    <script src="js/reveal.js"></script>
    <script src="js/main.js"></script>
  </body>
</html>
贡献指南 欢迎贡献代码和提出改进建议！ 提交问题：发现 Bug 或有改进建议，请提交
Issue。 代码贡献：请先 Fork 本仓库，然后提交 Pull Request。 许可证 本项目采用
MIT 许可证。 希望这份 README.md 文件能帮助你更好地理解和使用 OneSlide 工具！
```
