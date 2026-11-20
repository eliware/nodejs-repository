# Node.js package repository

This repository stores RPMs made from the official precompiled Node.js 26 Linux x64 binaries and release data for CentOS Stream 10 EPEL.

The packaging pipeline writes signed RPM repository data, public signing keys, release catalogs, manifests, provenance, validation records, and build evidence. This repository contains publication output. It is not the package build source.

Store stable RPM data below `el10/x86_64/stable/`. Store immutable generations below `.generations/`. The catalog marks preview releases unavailable. The pipeline does not publish preview paths or pointers.

The HTTP service in [nodejs-http](https://github.com/eliware/nodejs-http) serves this tree as read-only content. Make package and release changes through the pipeline in [nodejs-packaging](https://github.com/eliware/nodejs-packaging).

Read the packaging repository's [release contract](https://github.com/eliware/nodejs-packaging/blob/main/docs/RELEASE-CONTRACT.md) for the shared metadata and publication rules.
