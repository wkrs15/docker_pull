### Docker镜像
```
sudo vi /etc/docker/daemon.json
```
```
{
    "registry-mirrors": [
        "https://docker.wkrs14.top",
        "https://docker.m.daocloud.io",
        "https://docker.1panel.live",
        "https://hub.rat.dev"
    ]
}
```
```
sudo service docker restart
```
