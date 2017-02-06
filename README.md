# awesome-metrics 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome metrics platforms &amp; frameworks, ressources and other awesomeness.

Contributions are always welcome!

## Metrics collectors
* [Collectd](https://collectd.org/) - Daemon which collects system and application performance metrics periodically and provides mechanisms to store the values in a variety of ways, for example in RRD files.
* [Telegraf](https://docs.influxdata.com/telegraf/) - The plugin-driven server agent for collecting & reporting metrics.
* [Statsd](https://github.com/etsy/statsd) - Daemon for easy but powerful stats aggregation.
* [Diamond](http://diamond.readthedocs.io/) - Python daemon that collects system metrics and publishes them to Graphite (and others).
* [Phantomas](https://github.com/macbre/phantomas/) - PhantomJS-based web performance metrics collector and monitoring tool.
* [Logster](https://github.com/etsy/logster/) - Parse log files, generate metrics for Graphite and Ganglia.

## Metrics databases
* [InfluxDB](https://influxdata.com) - Scalable datastore for metrics, events, and real-time analytics.
* [KairosDB](http://kairosdb.github.io/) - Cassandra backed time series database, initially a fork of OpenTSDB.
* [Kenshin](https://github.com/douban/Kenshin/) - A time-series database alternative to Graphite Whisper with 40x improvement in IOPS.
* [Metrictank](https://github.com/raintank/metrictank/) - Cassandra-backed, metrics2.0 based, multi-tenant timeseries database for Graphite and friends.
* [OpenTSDB](http://opentsdb.net/) - A time series database running on top of HBase.
* [Prometheus](https://prometheus.io/) - Monitoring system and time series database. 
* [Warp 10](http://www.warp10.io/) - Complete (Geo) Time Series platform, handles storage and analytics via a dedicated language called WarpScript. Runs from Raspberry Pi to large clusters on HBase.
* [Whisper](https://github.com/graphite-project/whisper/) - File-based time-series database format for Graphite.

## Metrics UI
* [Grafana](http://grafana.org/) - Beautiful metric & analytic dashboards.
* [Graphene](http://jondot.github.io/graphene/) - Realtime dashboard & graphing toolkit based on D3 and Backbone. 
* [Tessera](http://tessera-metrics.github.io/tessera/) - A dashboard front-end for graphite.

## Metrics frameworks
* [Dropwizard](http://www.dropwizard.io/) - Dropwizard is a Java framework for developing ops-friendly, high-performance, RESTful web services.
* [Stagemonitor](http://www.stagemonitor.org/) - An open source solution to application performance monitoring for java server applications.
* [Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/) - Sub-project of Spring Boot that provides endpoints allow you to monitor and interact with your application: health, metrics, etc.
* [Metrics](https://github.com/mikejihbe/metrics/) - A node.js port of codahale's metrics library.
* [Go-metrics](https://github.com/rcrowley/go-metrics) - A Go port of codehale's metrics library.

## Real world dashboards

* [Gitlab](http://monitor.gitlab.net/) - Gitlab monitor dashboard: CI, HAProxy, Postgres, Redis, etc.
* [Percona](https://pmmdemo.percona.com/graph/dashboard/db/pmm-demo) - Percona Monitoring and Management: MongoDB, MySQL, Prometheus, etc.
