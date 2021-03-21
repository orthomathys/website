# Ortho Mathys Website

Website for an orthopedic shoemaker based in Seftigen.

It is based on the work of:

* https://github.com/jeromelachaud/freelancer-theme/
* https://github.com/StartBootstrap/freelancer-jekyll/


## Test locally using podman

```bash
podman run --name jekyll --rm --tty --env 'TZ=Europe/Zurich' --volume "$PWD:/srv/jekyll:z" -it -publish 4000:4000 docker.io/jekyll/jekyll jekyll serve
```
