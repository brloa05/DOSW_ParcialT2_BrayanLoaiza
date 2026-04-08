# comando para correr la base de datos en docker
docker run --name postgres-lab8 -e POSTGRES_DB=mydb -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
