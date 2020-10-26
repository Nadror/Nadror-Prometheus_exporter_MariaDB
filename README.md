# **Nadror-Prometheus_exporter_MariaDB**
---
# How to start Docker-compose
## Prerequisites

* **Docker & Docker-compose package**

#
At the begenning you need to clone the repo :

```sh
git clone https://github.com/Nadror/Nadror-Prometheus_exporter_MariaDB.git
```
After this you launch the docker-compose :

```sh
docker-compose up -d
```

Usually **3** dockers have been created

You can check that with this command :

```sh
docker ps -a
```


Now we can try to go to the GUI of Prometheus :

Type on your browser ```http://localhost:9090/graph``` or ```http://ServerIP:9090/graph```


