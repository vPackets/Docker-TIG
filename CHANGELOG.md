Docker StatsD InfluxDB Grafana image
-----------------------------------

## v3.0
Upgraded Grafana 5.3.2
Upgraded Telegraf 1.8.2.1
Upgraded InfluxDB 1.6.4
Upgraded Chronograf 1.6.2

Automation and Integration:
* InfluxDB Database creation
* Grafana Data Source creation based on InfluxDB
* Grafana Dashboard automated
* Telegraf configuration to pull data to CSR1000v 
* Interface Bandwith monitoring
* Uptime monitoring
* Number of SIP calls monitoring
        


## Forked - Goals

* Some improvements regarding how things are automated.

## v2.1.0 (2018-06-11)

* Upgraded Grafana 5.1
* Installed Chronograf 1.5

## v2.0.0 (2017-01-28)

### Warning: upgrade from version 1.0.x is not supported, all persisted data in volumes will be lost if you delete the container.

* Ubuntu 16.04 LTS is the new Docker base image
* New init system with Supervisord
* StatsD InfluxDB backend connector removed
* StatsD Etsy removed
* StatsD has been fully replaced with InfluxData Telegraf, that supports StatsD protocol
* Upgraded InfluxDB to version 1.2
* Upgraded Grafana to version 4.1.1

## v1.0.2 (2016-09-15)

* Fix for bad proxy hash sum mismatch

## v1.0.1 (2016-06-27)

* Upgraded StatsD to version 0.8.0
* Upgraded InfluxDB to version 0.13.0
* Upgraded Grafana to version 3.0.4
* Changed StatsD backend connector for InfluxDB new version

## v1.0.0 (2015-07-19)

* Initial release
