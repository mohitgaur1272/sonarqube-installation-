# sonarqube-installation-

## first of all create these all directrios
```
sudo mkdir -p /opt/sonarqube/data
sudo mkdir -p /opt/sonarqube/logs
sudo mkdir -p /opt/sonarqube/extensions
sudo chown -R ubuntu:ubuntu /opt/sonarqube
sudo chown -R 999:999 /opt/sonarqube
```
## then create docker-compose.yml file and then run by this cmd
```
docker-compose up -d
```
