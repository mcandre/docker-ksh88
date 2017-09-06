# docker-ksh88: A docker image for ksh88

# ABOUT

It is difficult to find a Linux package for ksh88 proper, but fortunately we can rely on the fact that pdksh is a clone of ksh88, so a system with `/bin/pdksh` soft-linked to `/bin/ksh88` is helpful for running any old ksh88 scripts you have lying around.

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-ksh88/

# EXAMPLE

```console
$ docker run mcandre/docker-ksh88 ksh88 -c "echo hello"
hello
```
