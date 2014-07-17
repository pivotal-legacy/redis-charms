# Overview

This charm provides redis (http://redis.io) service. It creates a redis master node. Redis is an open source, BSD licensed, advanced key-value store. It is often referred to as a data structure server since keys can contain strings, hashes, lists, sets and sorted sets.

# Usage

Step by step instructions on using the charm:

```
    juju deploy redis-master
```

Defaults:
    Redis version : 2.8.12
    Port : 6379

You can change these values by providing your config file setting version or port properties.

To install redis version 2.8.8, listening on port 6380:

```
    juju deploy redis-master --config ~/redis-config.yml
```

Where ~/redis-config.yml contains:

```
redis-master:
  version: 2.8.8
  port: 6379
```

## Scale out Usage


## Known Limitations and Issues


# Configuration

# Contact Information

## Upstream Project Name

- Upstream website
- Upstream bug tracker
- Upstream mailing list or contact information
- Feel free to add things if it's useful for users
