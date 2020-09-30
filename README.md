# grafana-dashboards-elasticsearch

Grafana Dashboards for Elasticsearch using Prometheus Datasource.

## Requirements

- **Datasource**: [Prometheus](https://prometheus.io/)
- **Exporter**: [Elasticsearch Exporter](https://github.com/justwatchcom/elasticsearch_exporter)

## Quickstart

My dashboards require **Prometheus** datasource for _mananging metrics_, and **Elasticsearch Exporter** for _crawling metrics_ from Elasticsearch Cluster and _exposing_ these metrics. Prometheus is scheduled for _pulling metrics_ from Elasticsearch Exporter.

<p align="center">
<img src="https://raw.githubusercontent.com/huynhsamha/grafana-dashboards-elasticsearch/master/img/architecure.jpg" alt="Architecture" width="70%">
</p>

I published my dashboards to [Grafana Dashboards](https://grafana.com/grafana/dashboards) so you can easily import these dashboards to your Grafana.

- `13071`: [Dashboard for Elasticsearch Cluster Stats](https://grafana.com/grafana/dashboards/13071)
- `13073`: [Dashboard for Elasticsearch Node Stats](https://grafana.com/grafana/dashboards/13073)
- `13072`: [Dashboard for Elasticsearch Index Stats](https://grafana.com/grafana/dashboards/13072)
- `13074`: [Dashboard for Elasticsearch History Stats](https://grafana.com/grafana/dashboards/13074)

Many thanks to https://grafana.com/grafana/dashboards/6483 and https://grafana.com/grafana/dashboards/2322

## Screenshots

| Dashboard         |                                                                                    Screenshot                                                                                    |
| ----------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Cluster Stats** |    <img src="https://raw.githubusercontent.com/huynhsamha/grafana-dashboards-elasticsearch/master/screenshots/es-cluster-dashboard.jpg" alt="ES Cluster Stats" width="400px">    |
| **Node Stats**    |    <img src="https://raw.githubusercontent.com/huynhsamha/grafana-dashboards-elasticsearch/master/screenshots/es-node-stats-dashboard.jpg" alt="ES Node Stats" width="400px">    |
| **Index Stats**   |   <img src="https://raw.githubusercontent.com/huynhsamha/grafana-dashboards-elasticsearch/master/screenshots/es-index-stats-dashboard.jpg" alt="ES Index Stats" width="400px">   |
| **History Stats** | <img src="https://raw.githubusercontent.com/huynhsamha/grafana-dashboards-elasticsearch/master/screenshots/es-history-stats-dashboard.jpg" alt="ES History Stats" width="400px"> |

## Changelogs

- **30/09/2020**: first release with 4 dashboards, including [Cluster Level Stats](https://grafana.com/grafana/dashboards/13071), [Node Stats](https://grafana.com/grafana/dashboards/13073), [Index Stats](https://grafana.com/grafana/dashboards/13072) and [History Stats](https://grafana.com/grafana/dashboards/13074)
