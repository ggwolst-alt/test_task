#назначаем базовый образ в данном случаи nginx стабильной версии
FROM nginx:stable 

#Копируем файл конфигурации nginx в контейнер
COPY index.html /usr/share/nginx/html/index.html

#назначаем внутренний порт контейнера
EXPOSE 80
