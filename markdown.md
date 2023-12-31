## Markdown语法

1. ### 图片

   在 Markdown 中展示图片，可以使用以下的语法：
   ```markdown
   ![替代文本](图片链接地址)
   ```
   其中：
   - 替代文本是指图片无法显示时的替代文本描述。
   - 图片链接地址是指图片的 URL 地址或者相对路径（如果图片存储在本地或者相对于 Markdown 文件的位置）。

   示例：
   ```markdown
   ![可爱熊猫](https://example.com/panda.jpg)
   ```
   这样的语法将会在文档中展示一张名为"可爱熊猫"的图片。

   如果要设置图片尺寸，在 Markdown 中，可以使用 HTML 标签来设置图片的尺寸。例如，你可以通过`<img>`标签并指定`width`和`height`属性来设置图片的尺寸，如下所示：

   ```html
   <img src="https://example.com/panda.jpg" width="300" height="200">
   ```

   上述示例中，`width`属性设置图片的宽度，`height`属性设置图片的高度。这样，在 Markdown 中使用 HTML 标签可以让你更精确地控制图片的尺寸。

2. ### 列表

   使用以下的 markdown 语法来创建不同类型的列表：

   - 无序列表使用 "-"、"+" 或 "*" 开头，示例：


   ```markdown
   - 项目一
   - 项目二
   - 项目三
   ```

   - 有序列表使用数字加上英文句点开头，示例：


   ```markdown
   1. 项目一
   2. 项目二
   3. 项目三
   ```

   - 嵌套列表则在子列表中添加缩进：


   ```markdown
   - 主项目
     - 子项目
     - 子项目
   - 主项目
   ```

   以上所示的 markdown 语法将会渲染为相应的列表格式。

3. ### 字体变化

   使用以下的markdown语法来实现不同的字体样式：

   - *斜体*：`*斜体*` 或 `_斜体_`
   - **粗体**：`**粗体**` 或 `__粗体__`
   - ***粗斜体***：`***粗斜体***`
   - ~~删除线~~：`~~删除线~~`

   举例来说，输入`*斜体*`将显示为*斜体*，输入`**粗体**`将显示为**粗体**。