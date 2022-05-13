To access etcd metrics, you need to run master nodes with   
***--etcd-expose-metrics=true*** flag.
After restarting the k3s-server service,  
the metrics will be available by the following endpont:  
         ***%master-node-ip%:2381/metrics***
this endpoint must be added to the static config of Prometheus server
