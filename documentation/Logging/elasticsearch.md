# Elasticsearch

"Elasticsearch is a real-time, distributed storage, search, and analytics engine."

## Features

1. Distributed storage
2. Data redundancy
3. Full text searching
4. Load balancing
5. API based interaction
6. YAML format config files

### Configuration

##### Java

Installation requires Java 8 or higher. Only Oracle Java and OpenJDK are supported, Elasticsearch will refuse to start with a known-bad version of Java is used. The same Java version is recommended on all hosts. Supported versions: [https://www.elastic.co/support/matrix](https://www.elastic.co/support/matrix "Support Matrix")

##### Config files

Elasticsearch has three configuration files located in the config directory:

* `elasticsearch.yml`
  for configuring Elasticsearch
* `jvm.options`
  for configuring Elasticsearch JVM settings
* `log4j2.properties`
  for configuring Elasticsearch logging



