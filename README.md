<h1 align="center">Expo CLI - Docker</h1>
<h4 align="center">Sample set up of Expo within a Docker environment</h4>

# Table of Contents
- [Requirements](#requirements)
- [Prerequisite Commands](#prerequisite-commands)
- [Common Issues and Workarounds](#common-issues-and-workarounds)
    - [Metro Bundler](#metro-bundler)
    - [Local Area Network (LAN) Host Name](#lan)
- [Additional Resources](#additional-resources)


## Prerequisite Commands
```bash
1-create docker image from docker file
    ./build.sh
2- create container
    ./run.sh .env

3- go to container 
    docker exec -it cnr-codeserver-expo /bin/bash

4-access on brower expo
    127.0.0.1:19006
5-access on browser code server
    127.0.0.1:8082   # docker-pm2-expo-cli
