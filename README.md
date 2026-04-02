# Cat Proxy Helm Chart

Данный Helm-чарт предназначен для развертывания прокси-сервера с цепочкой HTTP → Privoxy → Tor → SOCKS5 в кластере Kubernetes.

## Требования

- Kubernetes 1.19+
- Helm 3.2.0+
- (Опционально) Ingress Controller для проброса трафика через TLS.