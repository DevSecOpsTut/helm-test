# helm-test
A sample redis node helm repo

- cd node-redis-demo
- kubectl create namespace testns
- helm install test1  ./ -n testns
- helm uninstall test1 -n testns  