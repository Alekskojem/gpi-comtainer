# gpi-comtainer
Docker-Container with Grafana Influx Telegraf
1. Create catalog for example /opt/gpi/ on localhost
2. Copy files in place where you are make to start docler-compose.yml file: docker-compose.yml, influxv2.env.
3. Create catalogs grafana_data and make it is /opt/gpi# sudo chmod -R 775 /opt/gpi/grafana_data
4. Create catalo for influxdb /opt/gpi#mkdir influxdbv2 for database usage.
5. Create catalog for telegraf /opt/gpi#mkdir telegraf and create file insid mytelegraf.conf for telegraf
run: docker-compose up -d
Next open in your browser http://ip-localhost:8086 for influxdb2. Login and pass in .env file
Next open in your browser http://ip-localhost:3000 for grafana. Login and pass in docker-compose file.
