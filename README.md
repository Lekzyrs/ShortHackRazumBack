front link - https://github.com/Lekzyrs/ShortHackRazumFront

how to:

docker run --name postgres -e POSTGRES_DB=vapor_database
-e POSTGRES_USER=vapor_username
-e POSTGRES_PASSWORD=vapor_password
-p 5432:5432 -d postgres docker run --name postgres-test -e POSTGRES_DB=vapor-test
-e POSTGRES_USER=vapor_username
-e POSTGRES_PASSWORD=vapor_password
-p 5433:5432 -d postgres

swift run

postman basic auth: admin password
