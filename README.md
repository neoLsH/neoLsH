## About me

I'm a backend engineer at Alibaba (Qwen) in Guangzhou, working on web data infrastructure — large-scale page rendering and content acquisition services that sit between the open web and LLM applications.

Day to day I write Go, Java, Node.js/TypeScript and shell, and I care about reliability, observability, and keeping systems boring.

![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Nacos](https://img.shields.io/badge/Nacos-2A66CF?style=flat) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnubash&logoColor=white) ![AI Applications](https://img.shields.io/badge/AI_Applications-6366F1?style=flat) ![AI Coding](https://img.shields.io/badge/AI_Coding-14B8A6?style=flat) ![Harness](https://img.shields.io/badge/Harness-F59E0B?style=flat)

## Open source

Contributing to [Nacos](https://github.com/nacos-group), [Redis](https://github.com/redis/redis) and [Prometheus](https://github.com/prometheus). I enjoy the community side of open source and I'm interested in taking on more wherever I can be useful.

**Nacos** — server-side work and keeping the Node.js and Go SDKs consistent with the Java one:

- nacos server: log the resolved logging config location and add namespaceId to subscribe logs — [alibaba/nacos#15792](https://github.com/alibaba/nacos/pull/15792) (merged)
- nacos server: remove the prometheus dependency from nacos-client via a pluggable metrics SPI — [alibaba/nacos#15793](https://github.com/alibaba/nacos/pull/15793)
- add `selectOneHealthyInstance` to the Node.js naming client — [nacos-sdk-nodejs#152](https://github.com/nacos-group/nacos-sdk-nodejs/pull/152) (merged)
- align config local cache with the Java SDK (failover + snapshot lifecycle) — [nacos-sdk-nodejs#154](https://github.com/nacos-group/nacos-sdk-nodejs/pull/154)
- support `publishConfigCas` for optimistic-lock style config publish — [nacos-sdk-nodejs#153](https://github.com/nacos-group/nacos-sdk-nodejs/pull/153) (merged)
- always subscribe services loaded from local disk cache — [nacos-sdk-go#911](https://github.com/nacos-group/nacos-sdk-go/pull/911)
- fix the default value of `nacos.core.auth.enabled` in the auth docs — [nacos-group.github.io#1144](https://github.com/nacos-group/nacos-group.github.io/pull/1144)

**Redis**:

- fix keyspace notification event order for list move commands — [redis/docs#3855](https://github.com/redis/docs/pull/3855) (merged)

**Prometheus**:

- alertmanager: make silence creator and comment optional — [alertmanager#5471](https://github.com/prometheus/alertmanager/pull/5471) (merged)
- procfs: model legacy TcpExt counters removed from recent kernels — [procfs#863](https://github.com/prometheus/procfs/pull/863) (merged)
- node_exporter: use procfs parsers for netstat, snmp and snmp6 — [node_exporter#3796](https://github.com/prometheus/node_exporter/pull/3796) (merged)

**Other communities**:

- better-harness: attribute verdict source and guard green runs in the project docs — [better-harness#121](https://github.com/QoderAI/better-harness/pull/121) (merged)

## Interests

Distributed systems, distributed configuration and service discovery, web infrastructure, developer tooling, AI applications, AI coding and evaluation harnesses, and open-source communities.
