# Gunakan image dasar Nginx
FROM nginx:latest

# Salin file konfigurasi Nginx dari proyek Anda ke dalam container
COPY nginx.conf /etc/nginx/nginx.conf

# Salin direktori HTML ke dalam container
COPY html /usr/share/nginx/html

# Ekspos port 80
EXPOSE 80

# Jalankan Nginx dalam mode foreground
CMD ["nginx", "-g", "daemon off;"]
