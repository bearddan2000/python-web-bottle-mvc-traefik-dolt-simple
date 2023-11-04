# python-web-bottle-mvc-traefik-dolt-simple

## Description
Simple web app that serves static pages
for a bottle project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - bottle
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- dolt
- ssl

## Docker stack
- python:latest
- dolthub/dolt-sql-serverdb
- alpine:edge
- traefik:v2.4

## To run
`sudo ./install.sh -u`
- [Availble at](https://myapi.docker.localhost)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
