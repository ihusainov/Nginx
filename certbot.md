# Certbot config

```
certbot --config-dir ./config --work-dir ./work --logs-dir ./logs certonly --preferred-challenges dns --manual -d company.com --email admin@company.com --agree-tos
```
