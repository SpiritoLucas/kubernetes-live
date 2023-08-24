# Prometheus toolkit

Este repositorio cuenta con el stack de prometheus toolkit:
- alertmanagers
- node exporter
- kube-state-metrics


Cada branch representa el deployment para cada cluster.

Branch   | Cluster    |
------------- | -------------
Master           | production      
development            | development
        management         | management
        sandbox            | sandbox


# Deployment manual

``` kubectl apply -f prometheus.yaml -n monitoring ```
