---
title: Monitoring Voyager operator
menu:
  docs_6.0.0-rc.2:
    identifier: operator-stats-monitoring
    name: Monitoring Voyager operator
    parent: monitoring-ingress
    weight: 25
product_name: voyager
menu_name: docs_6.0.0-rc.2
section_menu_id: guides
info:
  version: 6.0.0-rc.2
---

# Monitoring Voyager operator

Voyager operator exposes Prometheus ready metrics via the following endpoints on port `:56790`:

- `/metrics`: Scrape this to monitor operator.

To change the port, use `--ops-address` flag on Voyager opreator.
