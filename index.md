---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

![logo]({{ site.url }}/images/logo.png)

## What

**Samaritan (səˈmerətn)** is a client side proxy that works on L4 or L7 layer written by golang, provide high availability and load balancing.
You can call it **Sam (sam)** for simplicity.

## Features

- Sidecar, lightweight

- Written by golang

- Hot re-configuration without downtime

- First-class Redis cluster support

- Good observability


[SOA]: https://en.wikipedia.org/wiki/Service-oriented_architecture
[Microservices]: https://en.wikipedia.org/wiki/Microservices
[HAProxy]: http://www.haproxy.org

[Bamboo]: https://github.com/QubitProducts/bamboo
[Synapse]: https://github.com/airbnb/synapse
[HAProxyHack]: http://engineeringblog.yelp.com/2015/04/true-zero-downtime-haproxy-reloads.html

## Status

It is deployed on every container and virtual machine in the production environment at ELEME, proxying all traffic to the basic components including Redis, MySQL, MQ, etc.
And the total number of running instances is close to fifty thousand.
