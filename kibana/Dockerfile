ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/kibana/kibana:${ELK_VERSION}
RUN kibana-plugin install https://github.com/opendistro-for-elasticsearch/alerting-kibana-plugin/releases/download/v1.13.0.0/opendistroAlertingKibana-1.13.0.0.zip

# RUN bin/kibana-plugin install https://d3g5vo6xdbdb9a.cloudfront.net/downloads/kibana-plugins/opendistro-alerting/opendistroAlertingKibana-1.13.0.0.zip

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
