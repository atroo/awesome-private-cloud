# Awesome Private Cloud
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of useful pieces of software to build your own cloud.

## Content

### Orchestration and Management
- [Rancher](http://rancher.com) - easy way to handle your services, grouped in stacks, that scale with a mouse-click

### Monitoring & Logging
- [Prometheus](https://prometheus.io/) - defacto standardized metrics protocols, supports labels for multidimensional markings of time series
- [Grafana](https://grafana.com) - beautiful open-source dashboard tool, supports a multitude of databases including elasticsearch, graphite and influxdb
- [cAdvisor](https://github.com/google/cadvisor) - exports prometheus compatible metrics of docker containers
- [InfluxDB](https://www.influxdata.com) - timeseries database, supported by grafana
- [Elasticsearch](https://www.elastic.co/de/products/elasticsearch) - world-famous document database with outstanding performance
- [Telegraf](https://github.com/influxdata/telegraf) - plugin based data transformation tool for gathering any kind of metrics and storing them in time series database

### Distributed Tracing
- [OpenTracing](http://opentracing.io) - fast evolving standard to trace requests over different systems, crucial for microservices
- [Hawkular](http://www.hawkular.org) - apm tool
- [Jaeger](https://github.com/uber/jaeger) - apm tool
