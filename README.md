# Loggin stack with fluentd, Elastisearch and Kibana

## Usage

Run `docker-compose -f stack.yml up` and wait.

You can start sending log messages to *:24222.

Or using Docker drivers: `--log-driver=fluentd --log-opt tag="grabt.listener.{{.ImageName}}.{{.Name}}.{{.ID}}"`

Kibana will be available at: <http://0.0.0.0:5601/>
