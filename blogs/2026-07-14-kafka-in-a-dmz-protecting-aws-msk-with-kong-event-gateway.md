---
title: "Kafka in a DMZ: Protecting AWS MSK with Kong Event Gateway"
url: "https://konghq.com/blog/engineering/protecting-aws-msk-with-kong-event-gateway"
date: "2026-07-14"
feed_url: "https://konghq.com/feed"
---
The MSK exposure problem Amazon MSK brokers live in private subnets by default. That's the right default. Kafka's protocol wasn't designed for untrusted networks — it has no concept of rate limiting, no built-in field-level encryption, and its ACL model a…
