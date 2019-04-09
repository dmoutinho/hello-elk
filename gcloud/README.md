- kubectl apply -f elasticsearch.yaml

- kubectl create configmap kibana-yml --from-file=kibana.yml

- kubectl apply -f kibana.yaml