Language: [English](README.md) | [Русский](README.ru.md)

# Hi, I'm foksk76

I build practical homelab and open-source projects around email infrastructure, syslog, ELK, monitoring, and event analysis.

The goal of these projects is to reproducibly run suspicious mail activity in a Kerio Connect lab, move logs through Logstash and Elasticsearch into metrics and Grafana / Kibana dashboards, and help engineers identify compromise signals, review events, and reduce the risk of repeat attacks.

## Featured project line: Kerio Connect Monitoring & Logging

A lab-friendly project family for:

- running a Kerio Connect lab
- forwarding and parsing syslog
- anonymizing real data for safe public use
- building dashboards in Grafana and Kibana

## Start here

1. [kerio-connect](https://github.com/foksk76/kerio-connect) — run the lab
2. [kerio-logstash-project](https://github.com/foksk76/kerio-logstash-project) — parse and normalize logs
3. [kerio-syslog-anonymizer](https://github.com/foksk76/kerio-syslog-anonymizer) — anonymize real data for demos and publication

## Project flow

```text
Kerio Connect lab -> Syslog -> Logstash -> Elasticsearch -> Grafana / Kibana
                                      -> anonymized sample data for public repos and blog posts
```

## Audience

- Homelab engineers who want a reproducible lab for monitoring email infrastructure.
- Sysadmins learning how syslog becomes searchable operational data.
- Security, DevSecOps, and monitoring engineers who need safe examples for demos or handoff.

## What you will find in my repositories

- Step-by-step READMEs with quick onboarding paths.
- Reproducible lab setup and validation notes.
- Public-safe test data approach for demos and publication.
- Practical documentation for handoff and reuse.
