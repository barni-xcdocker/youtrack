# Youtrack Standalone with docker-compose

![state](https://img.shields.io/badge/state-stable-brightgreen.svg)
![Version](https://img.shields.io/badge/YouTrack%20ver.%3A-2020.6.2904-brightgreen.svg)

**This configuration use official images**

[YouTrack](https://hub.docker.com/r/jetbrains/youtrack)

# How to use

Clone this repository

```
git clone https://github.com/Egregors/youtrack-docker-compose.git
```

## Configuration

```
sudo chown -R 13001:13001 backups && sudo chown -R 13001:13001 conf && sudo chown -R 13001:13001 data && sudo chown -R 13001:13001 logs
```

Run docker-compose

```
docker-compose up -d
```

Web Interface will be available on `http://youtrack.loc/`

