# poc


##bilance rater

# datasource postgresql
docker run --name bilance-postgresql \
 -e POSTGRES_PASSWORD=postgres \
 -e POSTGRES_USER=postgres \
 -e POSTGRES_DB=bilance \
 -p5432:5432 \
 -d postgres
