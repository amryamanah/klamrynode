# klamrynode

 rover subgraph publish klamry@current \
  --routing-url http://locations.prod.svc.cluster.local:4001/graphql \
  --schema ./locations.graphql \
  --name locations

rover subgraph publish klamry@current \
  --routing-url http://reviews.prod.svc.cluster.local:4001/graphql \
  --schema ./reviews.graphql \
  --name reviews