# Monitoring components


## Deployment
Export the following environment variables (replace `password` with a strong password):
```shell
export INFLUXDB_USERNAME=admin
export INFLUXDB_PASSWORD=password
export INFLUXDB_ORG=entropy
export INFLUXDB_BUCKET=entropy
export INFLUXDB_RETENTION=365d
```
For test deployments you can customize the `.env.template` file and rename it into `.env`.
Consequently run:
```shell
docker-compose up -d
```