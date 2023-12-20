# Docker mod to update mesa-va-drivers to 23.3

[This mod fixes VAAPI devices initializing correctly allowing hardware acceleration.
See: https://github.com/linuxserver/docker-emby/issues/41](https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests/24174)

In emby docker arguments, set an environment variable `DOCKER_MODS=jbouhd/docker-mods:docker-emby-mesa-23.3.1`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=jbouhd/docker-mods:docker-emby-fix-vaapi|linuxserver/mods:docker-emby-mod2`
