---
title: Voyager
menu:
  docs_6.0.0-rc.2:
    identifier: voyager
    name: Voyager
    parent: reference
    weight: 0
product_name: voyager
menu_name: docs_6.0.0-rc.2
section_menu_id: reference
aliases:
- /docs/6.0.0-rc.2/reference/
info:
  version: 6.0.0-rc.2
---

## voyager

Voyager by Appscode - Secure Ingress Controller for Kubernetes

### Synopsis

Voyager by Appscode - Secure Ingress Controller for Kubernetes

### Options

```
      --alsologtostderr                  log to standard error as well as files
      --analytics                        Send analytical events to Google Analytics (default true)
  -h, --help                             help for voyager
      --log.format logFormatFlag         Set the log target and format. Example: "logger:syslog?appname=bob&local=7" or "logger:stdout?json=true" (default "logger:stderr")
      --log.level levelFlag              Only log messages with the given severity or above. Valid levels: [debug, info, warn, error, fatal] (default "info")
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files
      --stderrthreshold severity         logs at or above this threshold go to stderr
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [voyager check](/docs/6.0.0-rc.2/reference/voyager_check)	 - Check Ingress
* [voyager export](/docs/6.0.0-rc.2/reference/voyager_export)	 - Export Prometheus metrics for HAProxy
* [voyager haproxy-controller](/docs/6.0.0-rc.2/reference/voyager_haproxy-controller)	 - Synchronizes HAProxy config
* [voyager run](/docs/6.0.0-rc.2/reference/voyager_run)	 - Launch Voyager Ingress Controller
* [voyager version](/docs/6.0.0-rc.2/reference/voyager_version)	 - Prints binary version number.

