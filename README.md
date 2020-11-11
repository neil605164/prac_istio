# Prac Istio Secure Ingress

- 練習 443 連線進入服務，若 80 連線則強至轉 443
- [建立憑證教學(包含泛域名)](https://hackmd.io/fqGmqI6aQuqva9hFHt8R8g)

### 創立 secret 至 ingress gateway
```
kubectl create -n istio-system secret tls <secret name>> --key=<憑證.key>> --cert=<憑證.crt>
```