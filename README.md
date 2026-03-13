 #IMPORT TO DATABASE
psql --username=username --dbname=database_name -f filename.sql

#EXPORT/DUMB DATABASE IN SQL FILE
pg_dump -cC --inserts -U freecodecamp salon > salon.sql
