FROM fluent/fluentd:v1.14.0-debian-1.0
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.3"]
RUN ["gem", "install", "fluent-plugin-kafka", "--no-document", "--version", "0.17.3"]
RUN ["gem", "install", "fluent-plugin-multi-format-parser", "--no-document", "--version", "1.0.0"]
