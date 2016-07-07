![Druid Plugin Logo](https://raw.githubusercontent.com/grafana-druid-plugin/druidplugin/master/img/druid_logo.png)

# Grafana plugin for [Druid](http://druid.io/) real-time OLAP database for Grafana 3.0.

![Screenshot](https://raw.githubusercontent.com/grafana-druid-plugin/druidplugin/master/img/AddDataSource.png)
![Screenshot](https://raw.githubusercontent.com/grafana-druid-plugin/druidplugin/master/img/ListDataSource.png)
![Screenshot](https://raw.githubusercontent.com/grafana-druid-plugin/druidplugin/master/img/DruidPanel.png)

## Status

This plugin is built on the top of an existing Druid plugin (https://github.com/grafana/grafana-plugins)  which used to work on older Grafana versions. With the UI changes done on Grafana-3.0 the existing plugin stopped working. Lot of changes have been made to have it work on Grafana 3.0. It supports timeseries, group by, topN and Select queries.

Lot of features might still not be implemented. Your contributions are welcome.

## Plugin development history

This plugin was originally developed by Quantiply Corporation (Supported for Grafana versions < 2.5): https://github.com/grafana/grafana-plugins/tree/master/datasources/druid

This plugin was further enhanced by Carl Bergquist (https://github.com/grafana/grafana/pull/3328) (to support it on Grafana version 2.5 & 2.6).

I cloned the source from the Pull Request by Carl Bergquist and changed the plugin to have it work on Grafana-3.0.

All the credits for the original code and enahcement to 2.5 goes to Quantiply and Carl Bergquist. 

Opensourcing all the changes done to the plugin to support Grafana-3.0.
