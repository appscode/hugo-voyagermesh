---
title: Release | Voyager
description: Voyager Release
menu:
  docs_v12.0.0:
    identifier: release
    name: Release
    parent: developer-guide
    weight: 15
product_name: voyager
menu_name: docs_v12.0.0
section_menu_id: setup
info:
  version: v12.0.0
---

# Release Process

The following steps must be done from a Linux x64 bit machine.

- Do a global replacement of tags so that docs point to the next release.
- Push changes to the release-x branch and apply new tag.
- Push all the changes to remote repo.
- Build and push voyager & HAProxy docker images:

```console
$ cd ~/go/src/github.com/appscode/voyager
./hack/release.sh
```

- Now, update the release notes in Github. See previous release notes to get an idea what to include there.
