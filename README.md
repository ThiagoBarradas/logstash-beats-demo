# ELKB (Elasticsearch + Logstash + Kibana + Beats) 6.4.0 with Docker

First all, add host in your machine:

```
127.0.0.1    elasticsearch.local
127.0.0.1    kibana.local
```

Running stack:
```
docker-compose up -d
```

* User `elastic` and password `123change...`
* Elasticsearch: http://elasticsearch.local
* Kibana: http://kibana.local
* For logstash demo, see confs in `logstash/conf` dir
* CSV used to load data is in `logstash/csv` dir
* For elasticsearch configuration, see `elasticsearch.yml` in `elasticsearch/config` dir
* Search for test `http://elasticsearch.local/hits-*/_search`
* Search for test `http://elasticsearch.local/filebeat-*/_search`


## How can I contribute?

Please, refer to [CONTRIBUTING](.github/CONTRIBUTING.md)

## Found something strange or need a new feature?

Open a new Issue following our issue template [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE.md)

## Did you like it? Please, make a donate :)

if you liked this project, please make a contribution and help to keep this and other initiatives, send me some Satochis.

BTC Wallet: `1G535x1rYdMo9CNdTGK3eG6XJddBHdaqfX`

![1G535x1rYdMo9CNdTGK3eG6XJddBHdaqfX](https://i.imgur.com/mN7ueoE.png)