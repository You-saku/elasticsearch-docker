# elasticsearch-docker

## Overview
Set up Elasticsearch and Kibana.

## setup
```
git clone git@github.com:You-saku/elasticsearch-docker.git
cd elasticsearch-docker
docker compose up -d
open http://localhost:5601
```

## login(Kibana)
```
Username：kibana_system
Password：Password
```

## health check
```
curl -XGET "http://localhost:9200/_cat/health?v&pretty"
```

## reference
* [[v8.6] Elasticsearch/Kibanaをdocker-composeでインストールする手順](https://qiita.com/takeo-furukubo/items/c2f194679afadc06a4e9#kibana-%E3%83%AD%E3%82%B0%E3%82%A4%E3%83%B3)
