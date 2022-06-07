## nginx loadbalancer configuration.md





```bash
upstream backend{
        server localhost:8081;
        server localhost:8082;
}
server {
        listen 80;
        location / {
           proxy_pass http://backend;
        }
}
```
