# Python3 - Docker mod

This mod adds a python3 to the docker container, to be installed/updated during container start.

In docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:code-server-python3`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:code-server-python3|linuxserver/mods:code-server-mod2`

Based on 
https://github.com/linuxserver/docker-mods/tree/code-server-python3