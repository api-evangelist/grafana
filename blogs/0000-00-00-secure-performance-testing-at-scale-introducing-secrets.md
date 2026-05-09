---
title: "Secure performance testing at scale: Introducing secrets management for Grafana Cloud k6"
url: "https://grafana.com/blog/introducing-secrets-management-for-grafana-cloud-k6/"
date: ""
author: "Facundo Batista"
feed_url: "https://grafana.com/blog/index.xml"
---
To simulate real user behavior, performance tests often rely on API keys, tokens, or credentials to interact with real systems. But as your testing suite grows, this sensitive data can start to sprawl across scripts, configs, and environments, increasing the risk of exposure and making tests harder to manage and maintain. To address this challenge, we’re rolling out secrets management for Grafana Cloud k6, the fully managed performance testing platform powered by k6 OSS. Secrets management allows you to securely store and use sensitive values in your load tests.
