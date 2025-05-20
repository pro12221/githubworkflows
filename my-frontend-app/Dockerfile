# 使用 Nginx 官方最新稳定版作为基础镜像
FROM nginx:stable-alpine

# 将本地的 HTML/CSS/JS 文件复制到 Nginx 的默认静态文件目录
COPY index.html /usr/share/nginx/html/index.html
COPY style.css /usr/share/nginx/html/style.css
COPY script.js /usr/share/nginx/html/script.js

# 暴露 Nginx 的默认 HTTP 端口
EXPOSE 80

# Nginx 默认会启动，无需 CMD 指令
