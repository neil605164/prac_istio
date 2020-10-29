# Prac Istio Ingress with particular domain and path

- 測試指令
```
curl -I -HHost:httpbin.example.com http://$INGRESS_HOST:$INGRESS_PORT/headers
```