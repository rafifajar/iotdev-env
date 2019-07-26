# esp32bleprinter-Dockerfile
Repository to integrate Dockerfile with docker-hub 
[docker-hub link]
(https://hub.docker.com/r/rafifh/iotdev-env)

## Build Dockerfile
First, before build a Dockerfile, please clone this repo

```bash
git clone https://github.com/rafifajar/iotdev-env
```
after cloning repo, you can build Dockerfile, open your directory where the dockerfile is stored, and run

```bash
docker build -t tagname:version <Dockerfile location>
```
you can edit tagname and version as you need, and you can use "." for dockerfile location if you run in dockerfile directory
