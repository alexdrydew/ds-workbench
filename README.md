# ds-workbench
MLFlow installation based on docker-compose.

## About

This is a fork of https://github.com/Gorcenski/ds-workbench.

## Setup

You will need Docker installed.

Clone the repo. Edit `default.env`, or create a new `env` file, with your own preferred secrets.

Run the services using `docker-compose --env-file default.env up -d`, substituting if necessary your custom environment file.
