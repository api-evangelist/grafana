---
title: "Eliminate noisy log lines with Adaptive Logs drop rules"
url: "https://grafana.com/blog/eliminate-noisy-log-lines-with-adaptive-logs-drop-rules/"
date: ""
author: "Steven Dungan"
feed_url: "https://grafana.com/blog/index.xml"
---
Most platform and observability teams have logs they know are noise. These could be throwaway health check logs, forgotten DEBUG logs, or verbose INFO logs from little used services that only serve to inflate your bill.Regardless of what they contain and why they're there in the first place, the hard part is getting rid of them. Centralized teams want to easily and quickly prevent these logs from being ingested, without having to work with toilsome infrastructure change management to do so. There hasn't been a simple way to use Grafana Cloud to drop them—until now.
