# sunshine-2021
My challenge for SunshineCTF 2021

# How to run

Either cd to `dynamic_type_librarii/deploy` and run `docker-compose --project_name dynamic_type_librarii up --build` or run the convenience script `./deploy.sh`

# What to provide

The files in `dist` should be provided. They should be up to date, but they will automatically be rebuilt when `docker-compose up` is run to ensure competitors have the most recent files.

# Description

The description is in `chal.json`

# Solver

The solver is in `solve` if you need a health check set host and port appropriately.

# Port

Right now, the challenge runs on port 1400. If you want to change the port *only* change it in `docker-compose.yml`.
