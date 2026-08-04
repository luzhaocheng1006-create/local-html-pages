# Local HTML Pages

用于将本机生成的、可以公开分享的 HTML 文件发布为外部可访问链接。

## 使用方法

1. 把 HTML 文件复制到仓库根目录。
2. 提交并推送：

   ```bash
   git add 文件名.html
   git commit -m "Publish 文件名"
   git push
   ```

3. 等待 GitHub Pages 更新后，通过以下格式访问：

   ```text
   https://luzhaocheng1006-create.github.io/local-html-pages/文件名.html
   ```

文件名含中文或空格时，浏览器会自动进行 URL 编码。

> 仓库与 Pages 站点均为公开状态。上传前请确认文件不含密码、客户信息、订单信息、访问令牌或其他敏感内容。
