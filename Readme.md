# Prometheus

- prometheus ･･･ 監視サーバ
- exporter ･･･ 監視対象

## node exporter

[各種exporter](https://prometheus.io/docs/instrumenting/exporters/)

```
docker run -d -p 9100:9100 --net="host" prom/node-exporter
```

## Grafana

初期パスワード: admin/admin

pluginでVisualizationを開発することができる
http://docs.grafana.org/plugins/developing/development/