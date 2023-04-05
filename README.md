# IntermediateFlaskLab_SD_PY_Starter


Setup Steps: 

run 'pipenv install' to ready virtual environment
run 'pipenv shell' to load virtual env
(run pip -V to check if in virtual env)

Getting database ready: 

open included sql file with 'reveal in file explorer' right click option

open sql workbench and drag/drop file to open

run first line to create database

can create migrations with 'flask db init', then 'flask db migrate -m "Init"' to create migration file on model(s)

to tell flask to create tables in new database (linked through .env file), migrations already created, so use 'flask db upgrade', now see tables in sql workbench

(if changing model(s), need to do both previous steps, the migrate -m and db upgrade to commit the change and update the sql database)


run other 4 seed queries in file to seed data (need to move course query below instructor as course references instructor id before table is created)

Postman: 

under collections hit import, and drag/drop included file

VScode:

change path by clicking number at bottom (likely ending in 64bit) to open the 'select interpreter'

run pipenv --venv to get version address, copy and select 'enter interpreter path' at top and paste

