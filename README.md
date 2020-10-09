### Running the stack
To start the stack just `docker-compose up`

### Sending Heroku  logs to Logstash
Install and login using the Heroku CLI and execute:
`heroku drains:add <logstas_address>:1514 -a <Heroku app name>`