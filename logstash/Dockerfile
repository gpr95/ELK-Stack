FROM logstash:5
RUN logstash-plugin install logstash-input-kinesis && \
    logstash-plugin install logstash-codec-cloudwatch_logs && \
    logstash-plugin install logstash-output-amazon_es && \
    logstash-plugin install logstash-filter-aggregate && \
    logstash-plugin install logstash-filter-split
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
