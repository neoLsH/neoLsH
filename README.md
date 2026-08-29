## About me

I'm a backend engineer at Alibaba (Qwen) in Guangzhou, working on web data infrastructure — large-scale page rendering and content acquisition services that sit between the open web and LLM applications.

Day to day I write Go, Java, Node.js/TypeScript and shell, and I care about reliability, observability, and keeping systems boring.

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Nacos](https://img.shields.io/badge/Nacos-2A66CF?style=flat) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnubash&logoColor=white)

## Open source

Contributing to [Kubernetes](https://github.com/kubernetes/kubernetes), [Nacos](https://github.com/nacos-group), [Redis](https://github.com/redis/redis) and [Prometheus](https://github.com/prometheus). I enjoy the community side of open source and I'm interested in taking on more wherever I can be useful.

**Kubernetes** — currently in review:

- kubelet: mark pods NotReady on NotReady→Unknown node transition — [#141550](https://github.com/kubernetes/kubernetes/pull/141550)
- kubelet: defer to pod grace period when eviction-max-pod-grace-period is negative — [#141551](https://github.com/kubernetes/kubernetes/pull/141551)
- kube-controller-manager: contextual logging in the clustertrustbundle publisher controller — [#141553](https://github.com/kubernetes/kubernetes/pull/141553)
- migrate Deployment and ReplicaSet selector to declarative validation — [#141558](https://github.com/kubernetes/kubernetes/pull/141558)
- informer-gen: use plural-exceptions-aware namer for GVR resource name — [#141566](https://github.com/kubernetes/kubernetes/pull/141566)
- kubelet: add unit tests for secret manager implementations — [#141567](https://github.com/kubernetes/kubernetes/pull/141567)
- cluster-autoscaler: honor scale-down-delay-after-failure for async deletion failures — [cluster-autoscaler#79](https://github.com/kubernetes-sigs/cluster-autoscaler/pull/79)

**Nacos** — keeping the Node.js and Go SDKs consistent with the Java one:

- add `selectOneHealthyInstance` to the Node.js naming client — [nacos-sdk-nodejs#152](https://github.com/nacos-group/nacos-sdk-nodejs/pull/152) (merged)
- align config local cache with the Java SDK (failover + snapshot lifecycle) — [nacos-sdk-nodejs#154](https://github.com/nacos-group/nacos-sdk-nodejs/pull/154)
- support `publishConfigCas` for optimistic-lock style config publish — [nacos-sdk-nodejs#153](https://github.com/nacos-group/nacos-sdk-nodejs/pull/153)
- always subscribe services loaded from local disk cache — [nacos-sdk-go#911](https://github.com/nacos-group/nacos-sdk-go/pull/911)
- fix the default value of `nacos.core.auth.enabled` in the auth docs — [nacos-group.github.io#1144](https://github.com/nacos-group/nacos-group.github.io/pull/1144)

**Redis**:

- fix keyspace notification event order for list move commands — [redis/docs#3855](https://github.com/redis/docs/pull/3855) (merged)

**Prometheus**:

- alertmanager: make silence creator and comment optional — [alertmanager#5471](https://github.com/prometheus/alertmanager/pull/5471) (merged)
- procfs: model legacy TcpExt counters removed from recent kernels — [procfs#863](https://github.com/prometheus/procfs/pull/863) (merged)
- node_exporter: use procfs parsers for netstat, snmp and snmp6 — [node_exporter#3796](https://github.com/prometheus/node_exporter/pull/3796) (in review)

**Other communities**:

- better-harness: attribute verdict source and guard green runs in the project docs — [better-harness#121](https://github.com/QoderAI/better-harness/pull/121) (merged)

## Interests

Distributed systems, Kubernetes internals, distributed configuration and service discovery, web infrastructure, developer tooling, and open-source communities.
