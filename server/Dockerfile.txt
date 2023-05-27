
FROM python:latest

ADD server.py /server/
ADD index.html /server/

#команда `'WORKDIR'`позволяет изменить рабочую директорию образа
#В качестве такой директории, в которой будут выполняться все команды,  
#устанавливаем `'/server/'` 
WORKDIR /server/