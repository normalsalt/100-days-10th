# 100 Days Challenge 10th Period Archive

https://normalsalt.github.io/100-days-10th/

```
docker compose up -d
open http://localhost:1313/100-days-10th/
```

```
docker compose run --rm hugo hugo new content posts/100-days-10th.md
```

## installation

https://gohugo.io/installation/linux/

```
docker run --rm -v .:/content -w /content -it alpine:latest sh
apk add --no-cache --repository=https://dl-cdn.alpinelinux.org/alpine/edge/community hugo
hugo new site my-site
```

https://github.com/1bl4z3r/hermit-V2

```
git submodule add -b main https://github.com/1bl4z3r/hermit-V2 my-site/themes/hermit-v2
```

## deployment

https://gohugo.io/hosting-and-deployment/hosting-on-github/
