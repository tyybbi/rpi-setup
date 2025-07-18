# rpi-setup

My RaspberryPi setup with Grafana, Nginx reverse proxy, Docker, some RuuviTags
and Home Assistant Container.

Note: The setup uses external databases for Grafana and InfluxDB, so by itself
this won't be much of use for anyone but myself.

## How to run

Edit variables in `00-main.yml` as needed and run like
`ansible-playbook -i <your-rpi-address>, 00-main.yml -u <username> -kK`
