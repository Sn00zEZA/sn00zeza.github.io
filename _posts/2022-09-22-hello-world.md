---
title: Hello World
date: 2022-09-22 11:00:00 -500
categories: [homeblog, firstpost]
tags: [helloworld,firstpost,testing]
---

# Hello World

This is my first test post and I just went for the usual "Hello World" post to see how things work.

Inspired by Techno Tim:

[Techno Tim Jekyll Blog](https://docs.technotim.live/posts/jekyll-docs-site)

[Techno Time Jekyll Video](https://www.youtube.com/watch?v=F8iOU1ci19Q)

## Testing some Mark Down

* test1
* test2
* test3

```powershell
get-process | select name, id
```

```yaml
---
apiVersion: apps/v1beta1
kind: Deployment
metadata:
  name: hello-deployment
spec:
  replicas: 1
  template:
    metadata:
      labels:
        run: hello-world
    spec:
      containers:
      - name: hello
        image: nginxdemos/hello:latest
        ports:
        - containerPort: 80
```
## Images

![TwitterImage](https://pbs.twimg.com/profile_images/1443349680365129728/wKHRBSGS_400x400.jpg)