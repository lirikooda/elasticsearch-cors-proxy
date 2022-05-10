# Elasticsearch Proxy

This setup will allow accessing in-cluster elasticsearch service without worrying about ssl trust or cors.

Change anything in [docker-compose.yaml](docker-compose.yaml) if needed, that is service namespace etc, then run `docker-compose up` etc.

Once the setup is up, you can access elastic via either `https://localhost:9200`, or the "access free" `http://localhost:9201`.
