Инструкция по сборке:

выполнить команду в корне проекта:

docker build . -t vector

Для запуска выполнить команду 
docker run -d  -p 5050:5000 -v postgres_data:/var/lib/postgresql/data  vector:

предварительно создать volume командой:

docker volume create postgres_data
