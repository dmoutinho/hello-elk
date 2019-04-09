- kubectl apply -f elasticsearch.yaml

- kubectl create configmap kibana-yml --from-file=kibana.yml

- kubectl apply -f kibana.yaml

- kubectl create configmap logstash-conf --from-file=logstash.conf

- kubectl create configmap logstash-yml --from-file=logstash.yml