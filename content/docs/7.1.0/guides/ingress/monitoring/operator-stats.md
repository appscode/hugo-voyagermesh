---
title: Monitoring Voyager operator
menu:
  docs_7.1.0:
    identifier: operator-stats-monitoring
    name: Monitoring Voyager operator
    parent: monitoring-ingress
    weight: 25
product_name: voyager
menu_name: docs_7.1.0
section_menu_id: guides
info:
  version: 7.1.0
---

> New to Voyager? Please start [here](/docs/7.1.0/concepts/overview).

# Monitoring Voyager operator

Voyager operator exposes Prometheus ready metrics via the following endpoints on port `:56790`:

- `/metrics`: Scrape this to monitor operator.

To change the port, use `--ops-address` flag on Voyager opreator.
