# Graylog Instance Details

* MongoDB server
* Elasticsearch server
* Graylog server + Graylog web UI

Graylog is an open-source log management platform that is widely used for collecting, storing, and analyzing large volumes of log data from various sources. It provides a powerful and flexible way to monitor and troubleshoot IT infrastructure, applications, and security environments by centralizing log data and enabling real-time analysis.

<p align="center">
<img src="./archimage.png?raw=true">
</p>

##

Start the environment in the background

```
docker compose up -d
```

Stop the environment:

```
docker compose down
```


## Credits/Sources

* Tutorial Used: https://www.youtube.com/watch?v=DwYwrADwCmg&t=107s
* Tutorial Commands: https://forums.lawrencesystems.com/t/graylog-docker-tutorial-commands/17611
* Tutorial docs: https://github.com/lawrencesystems/graylog
* Graylog docs: https://go2docs.graylog.org/5-0/downloading_and_installing_graylog/ubuntu_installation.html 
* Docker docs: https://docs.docker.com/engine/install/ubuntu/