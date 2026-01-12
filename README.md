# 将你的头像图片放在以下位置：
# 头像图片：static/images/avatar.jpg (推荐 200x200 像素)
# Favicon文件：static/img/favicon.svg, static/img/favicon-32x32.png, static/img/favicon-16x16.png

# 文章中引用图片的方法：
# 1. 页面资源图片：放在 content/posts/你的文章名/ 目录下
# 2. 全局图片：放在 static/images/ 或 static/img/ 目录下

# 示例用法：
# 在文章中：![图片描述](avatar.jpg)  - 引用页面资源
# 在文章中：![图片描述](/images/avatar.jpg)  - 引用全局图片
# 在模板中：{{ .Site.Params.avatarurl }} - 引用配置中的头像
