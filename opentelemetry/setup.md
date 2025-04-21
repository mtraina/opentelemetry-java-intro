# setup
export JAVA_TOOL_OPTIONS="-javaagent:./opentelemetry/opentelemetry-javaagent.jar" \
OTEL_TRACES_EXPORTER=logging \
OTEL_METRICS_EXPORTER=logging \
OTEL_LOGS_EXPORTER=logging \
OTEL_METRIC_EXPORT_INTERVAL=15000