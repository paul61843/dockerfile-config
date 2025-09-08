FROM nginx:alpine

COPY conf/ /etc/nginx/

# 複製整個 html 資料夾到預設網站目錄
COPY html/ /usr/share/nginx/html/

EXPOSE 80

# 啟動 Nginx
CMD ["nginx", "-g", "daemon off;"]