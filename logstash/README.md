#Logstash

Run with:
```bash
docker run -d -p 5514:5514 -p 9600:9600 --network backnet --name logstash logstash:latest
```