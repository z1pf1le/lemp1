FROM nginx:latest

# Копирование настроек Nginx
COPY nginx.conf /etc/nginx/conf.d/nginx.conf

# Экспозиция порта
EXPOSE 80

# Запуск Nginx
CMD ["nginx", "-g", "daemon off;"]
