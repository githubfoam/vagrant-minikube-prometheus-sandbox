# vagrant-minikube-prometheus-sandbox
~~~~
vagrant destroy -f vg-mk-pro-02

vagrant up vg-mk-pro-02

    vg-mk-pro-02: NAME         READY   UP-TO-DATE   AVAILABLE   AGE
    vg-mk-pro-02: grafana      0/1     1            0           1s
    vg-mk-pro-02: prometheus   0/1     1            0           8s
    vg-mk-pro-02: NAME                          READY   STATUS              RESTARTS   AGE
    vg-mk-pro-02: grafana-5f78655c6-bkf25       0/1     ContainerCreating   0          1s
    vg-mk-pro-02: node-exporter-n67cr           0/1     ContainerCreating   0          0s
    vg-mk-pro-02: prometheus-6b8576d6d9-kjrwj   0/1     ContainerCreating   0          8s
    vg-mk-pro-02: NAME                              READY   STATUS              RESTARTS   AGE
    vg-mk-pro-02: pod/grafana-5f78655c6-bkf25       0/1     ContainerCreating   0          2s
    vg-mk-pro-02: pod/node-exporter-n67cr           0/1     ContainerCreating   0          1s
    vg-mk-pro-02: pod/prometheus-6b8576d6d9-kjrwj   0/1     ContainerCreating   0          9s
    vg-mk-pro-02:
    vg-mk-pro-02: NAME                 TYPE       CLUSTER-IP     EXTERNAL-IP   PORT(S)          AGE
    vg-mk-pro-02: service/grafana      NodePort   10.105.40.80   <none>        3000:30645/TCP   2s
    vg-mk-pro-02: service/prometheus   NodePort   10.96.203.10   <none>        9090:30599/TCP   8s
    vg-mk-pro-02: NAME         TYPE       CLUSTER-IP     EXTERNAL-IP   PORT(S)          AGE
    vg-mk-pro-02: grafana      NodePort   10.105.40.80   <none>        3000:30645/TCP   2s
    vg-mk-pro-02: prometheus   NodePort   10.96.203.10   <none>        9090:30599/TCP   8s

~~~~
~~~~
# https://prometheus.io/docs/prometheus/latest/getting_started/
~~~~
