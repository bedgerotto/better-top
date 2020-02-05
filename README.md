# Unix fancy monitor

Suite created based on the following post:

https://medium.com/schkn/monitoring-linux-processes-using-prometheus-and-grafana-113b3e271971

# Steps

## 1. Preparation
  Install docker and docker-compose

## 2. Startup
  Exec `docker-compose up`

## 3. Send data to Pushgateway

Grant execution permissiont to the better-top script and put it on your cron or, for tests porpuses, run:

`while sleep 1; do ./better-top; done;`

## 4. Configuring

Configure your Grafana dashboad following the previous mentioned medium post or, create your own.


# ToDo

[ ] Store Prometheus data in a volume

[ ] Store Grafana dashboard configuration