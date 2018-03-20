![GIFEE](images/title.png)

**GIFEE** is "Google's infrastructure for everyone else"

## Overview

- [Landscape](#landscape)
- [Papers](#papers)
- [Projects](#projects)
- [Community](#community)
- [FAQ](#faq)

## Landscape

[Joseph Jacks](https://twitter.com/asynchio) has put together a good reference to the mapping between Google and OSS tech.

![gstack](images/gstack.jpg)

- [https://twitter.com/asynchio/status/964536365185552389](https://twitter.com/asynchio/status/964536365185552389)

## Papers

Here's some papers to read. We'll be basing our tech off these starting with 2006 technologies.

- [The Google File System](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
- [The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)
- [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [MapReduce: Simplified Data Processing on Large Clusters](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)

More papers

- [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](http://www.australianscience.com.au/research/google/36356.pdf)
- [Large-scale cluster management at Google with Borg](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43438.pdf)
- [Megastore: Providing Scalable, Highly Available Storage for Interactive Services](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36971.pdf)
- [Spanner: Google’s Globally-Distributed Database](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)
- [Maglev: A Fast and Reliable Software Network Load Balancer](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf)

## Projects

Here's a list of existing projects based on or related to GIFEE

### Borg
- [Kubernetes](https://github.com/kubernetes/kubernetes) Production-Grade Container Scheduling and Management
- [Nomad](https://github.com/hashicorp/nomad) A Distributed, Highly Available, Datacenter-Aware Scheduler
- [Mesos](https://github.com/apache/mesos) A distributed systems kernel

### Borgmon
- [Prometheus](https://github.com/prometheus/prometheus) Systems monitoring and alerting toolkit

### BigTable
- [HBase](https://github.com/apache/hbase) A distributed, scalable, big data store

### Chubby
- [Zookeeper](https://github.com/apache/zookeeper) Highly reliable distributed coordination
- [Etcd](https://github.com/coreos/etcd) Distributed reliable key-value store

### GFS
- [Torus](https://github.com/coreos/torus) Torus Distributed Storage
- [HDFS](https://github.com/apache/hadoop-hdfs) A distributed Java-based file system

### Spanner
- [CockroachDB](https://github.com/cockroachdb/cockroach) A Scalable, Survivable, Strongly-Consistent SQL Database
- [TiDB](https://github.com/pingcap/tidb) A distributed HTAP database compatible with MySQL protocol

## Community

GIFEE has a slack at [gifee.slack.com](https://gifee.slack.com). Invite yourself at [slack.gifee.cloud](http://slack.gifee.cloud)

Follow on twitter at [@gifeecloud](https://twitter.com/gifeecloud)

## FAQ

### What does GIFEE mean?

GIFEE is an acronym for Google's Infrastructure for Everyone Else.

It's a term which has become a reference for open source equivalents of Google's technology.

### What is this repo?

GitHub/GIFEE is a place to experiment with ideas based on Google's infrastructure and for reference architectures.

### What will be built?

GIFEE will be a reference architecture for cloud-native based on Google technology.

### Will it be hosted?

GIFEE projects will likely be hosted at [gifee.cloud](http://gifee.cloud)

### Will it be Open Source?

Yes all GIFEE projects will be open source

### Can we contribute?

Yes. Whether it be reference architectures, docs, images, whatever. Please join in on the fun.

