---
title: Uninstall Voyager Community Edition
description: Uninstallation guide for Voyager Community edition
menu:
  docs_v2023.9.18:
    identifier: uninstall-voyager-operator
    name: Community Edition
    parent: uninstallation-guide
    weight: 10
product_name: voyager
menu_name: docs_v2023.9.18
section_menu_id: setup
info:
  cli: v0.0.14
  installer: v2023.9.18
  version: v2023.9.18
---

# Uninstall Voyager Community Edition

To uninstall Voyager Community edition, run the following command:

<ul class="nav nav-tabs" id="installerTab" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="helm3-tab" data-toggle="tab" href="#helm3" role="tab" aria-controls="helm3" aria-selected="true">Helm 3</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="script-tab" data-toggle="tab" href="#script" role="tab" aria-controls="script" aria-selected="false">YAML</a>
  </li>
</ul>
<div class="tab-content" id="installerTabContent">
  <div class="tab-pane fade show active" id="helm3" role="tabpanel" aria-labelledby="helm3-tab">

## Using Helm 3

In Helm 3, release names are [scoped to a namespace](https://v3.helm.sh/docs/faq/#release-names-are-now-scoped-to-the-namespace). So, provide the namespace you used to install the operator when installing.

```bash
$ helm uninstall voyager-operator --namespace voyager
```

</div>
<div class="tab-pane fade" id="script" role="tabpanel" aria-labelledby="script-tab">

## Using YAML (with helm 3)

If you prefer to not use Helm, you can generate YAMLs from the Voyager chart and uninstall using `kubectl`.

```bash
$ helm template voyager-operator appscode/voyager --namespace voyager | kubectl delete -f -
```

</div>
</div>
