# How to use MariaDB on DC/OS

[MariaDB](https://mariadb.org) is one of the most popular database servers in the world. It’s made by the original developers of MySQL and guaranteed to stay open source. Notable users include Wikipedia, Facebook and Google. MariaDB is developed as open source software and as a relational database it provides an SQL interface for accessing data. The latest versions of MariaDB also include GIS and JSON features.

**Table of Contents**:

- [Prerequisites](#prerequisites)
- [Install](#install)
- [Uninstall](#uninstall)

## Prerequisites

- A running DC/OS 1.9 cluster with at least 1 node having at least 1 CPUs and 1 GB of RAM available.
- [DC/OS CLI](https://dcos.io/docs/1.9/usage/cli/install/) installed.

## Install

## Uninstall

To uninstall MariaDB:

```bash
dcos package uninstall mariadb
```
