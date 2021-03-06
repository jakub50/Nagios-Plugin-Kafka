Kafka Scala API - Advanced Nagios Plugin / CLI Tool with Kerberos support
==============================

[![Codacy](https://api.codacy.com/project/badge/Grade/de500bf4f90d401ba5c98ed903c8a612)](https://www.codacy.com/app/harisekhon/nagios-plugin-kafka)
[![CodeFactor](https://www.codefactor.io/repository/github/harisekhon/Nagios-Plugin-Kafka/badge)](https://www.codefactor.io/repository/github/harisekhon/Nagios-Plugin-Kafka)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=HariSekhon_Nagios-Plugin-Kafka&metric=alert_status)](https://sonarcloud.io/dashboard?id=HariSekhon_Nagios-Plugin-Kafka)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=HariSekhon_Nagios-Plugin-Kafka&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=HariSekhon_Nagios-Plugin-Kafka)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=HariSekhon_Nagios-Plugin-Kafka&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=HariSekhon_Nagios-Plugin-Kafka)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=HariSekhon_Nagios-Plugin-Kafka&metric=security_rating)](https://sonarcloud.io/dashboard?id=HariSekhon_Nagios-Plugin-Kafka)
[![GitHub stars](https://img.shields.io/github/stars/harisekhon/Nagios-Plugin-Kafka)](https://github.com/harisekhon/Nagios-Plugin-Kafka/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/harisekhon/Nagios-Plugin-Kafka)](https://github.com/harisekhon/Nagios-Plugin-Kafka/network)
<!--
[![Dependency Status](https://www.versioneye.com/user/projects/57616d340a82b200276f6669/badge.svg)](https://www.versioneye.com/user/projects/57616d340a82b200276f6669)
-->

[![Linux](https://img.shields.io/badge/OS-Linux-blue?logo=linux)](https://github.com/HariSekhon/Nagios-Plugin-Kafka)
[![Mac](https://img.shields.io/badge/OS-Mac-blue?logo=apple)](https://github.com/HariSekhon/Nagios-Plugin-Kafka)
[![Docker](https://img.shields.io/badge/container-Docker-blue?logo=docker)](https://hub.docker.com/r/harisekhon/nagios-plugin-kafka)
[![DockerHub Pulls](https://img.shields.io/docker/pulls/harisekhon/nagios-plugin-kafka?label=DockerHub%20pulls&logo=docker)](https://hub.docker.com/r/harisekhon/nagios-plugin-kafka)
[![DockerHub Build Automated](https://img.shields.io/docker/automated/harisekhon/nagios-plugin-kafka.svg)](https://hub.docker.com/r/harisekhon/nagios-plugin-kafka)
[![Docker Build Status](https://img.shields.io/docker/cloud/build/harisekhon/nagios-plugin-kafka.svg)](https://hub.docker.com/r/harisekhon/nagios-plugin-kafka/builds)
[![MicroBadger](https://images.microbadger.com/badges/image/harisekhon/nagios-plugin-kafka.svg)](http://microbadger.com/#/images/harisekhon/nagios-plugin-kafka)
[![CI Builds Overview](https://img.shields.io/badge/CI%20Builds-Overview%20Page-blue)](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/STATUS.md)

[![Travis CI](https://img.shields.io/travis/harisekhon/Nagios-Plugin-Kafka/master?logo=travis&label=Travis)](https://travis-ci.org/HariSekhon/Nagios-Plugin-Kafka)
[![AppVeyor](https://img.shields.io/appveyor/build/harisekhon/Nagios-Plugin-Kafka/master?logo=appveyor&label=AppVeyor)](https://ci.appveyor.com/project/HariSekhon/Nagios-Plugin-Kafka/branch/master)
[![Drone](https://img.shields.io/drone/build/HariSekhon/Nagios-Plugin-Kafka/master?logo=drone&label=Drone)](https://cloud.drone.io/HariSekhon/Nagios-Plugin-Kafka)
[![CircleCI](https://circleci.com/gh/HariSekhon/Nagios-Plugin-Kafka.svg?style=svg)](https://circleci.com/gh/HariSekhon/Nagios-Plugin-Kafka)
[![Codeship Status for HariSekhon/Nagios-Plugin-Kafka](https://app.codeship.com/projects/faff7930-3c5f-0138-8a0b-32bf6ef9714a/status?branch=master)](https://app.codeship.com/projects/387257)
[![Shippable](https://img.shields.io/shippable/5e52c63620adbf000670adf6/master?label=Shippable)](https://app.shippable.com/github/HariSekhon/Nagios-Plugin-Kafka/dashboard/jobs)
[![Codefresh](https://g.codefresh.io/api/badges/pipeline/harisekhon/GitHub%2FNagios%20Plugin%20Kafka?branch=master&key=eyJhbGciOiJIUzI1NiJ9.NWU1MmM5OGNiM2FiOWUzM2Y3ZDZmYjM3.O69674cW7vYom3v5JOGKXDbYgCVIJU9EWhXUMHl3zwA&type=cf-1)](https://g.codefresh.io/pipelines/Nagios-Plugin-Kafka/builds)
[![Wercker](https://app.wercker.com/status/fe4f87bf98f31e4c22a3041c0966644b/s/master "wercker status")](https://app.wercker.com/project/byKey/fe4f87bf98f31e4c22a3041c0966644b)
[![BuildKite](https://img.shields.io/buildkite/3d50d0880ae9812f344ad5d6fe50768de24ce05be6ac74d582/master?label=BuildKite)](https://buildkite.com/hari-sekhon/nagios-plugin-kafka)
[![buddy pipeline](https://app.buddy.works/harisekhon/nagios-plugin-kafka/pipelines/pipeline/246985/badge.svg?token=7f63afa3c423a65e6e39a79be0386959e98c4105ea1e20f7f8b05d6d6b587038 "buddy pipeline")](https://app.buddy.works/harisekhon/nagios-plugin-kafka/pipelines/pipeline/246985)
[![Cirrus CI](https://img.shields.io/cirrus/github/HariSekhon/Nagios-Plugin-Kafka/master?logo=Cirrus%20CI&label=Cirrus%20CI)](https://cirrus-ci.com/github/HariSekhon/Nagios-Plugin-Kafka)
[![Concourse](https://img.shields.io/badge/Concourse-ready-blue)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/blob/master/.concourse.yml)
[![GoCD](https://img.shields.io/badge/GoCD-ready-blue)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/blob/master/.gocd.yml)
[![Jenkins](https://img.shields.io/badge/Jenkins-ready-blue)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/blob/master/Jenkinsfile)

[![Azure DevOps Pipeline](https://dev.azure.com/harisekhon/GitHub/_apis/build/status/HariSekhon.Nagios-Plugin-Kafka?branchName=master)](https://dev.azure.com/harisekhon/GitHub/_build/latest?definitionId=11&branchName=master)
[![BitBucket Pipeline](https://img.shields.io/bitbucket/pipelines/harisekhon/nagios-plugin-kafka/master?logo=bitbucket&label=BitBucket)](https://bitbucket.org/harisekhon/nagios-plugin-kafka/addon/pipelines/home#!/)
[![GitLab Pipeline](https://img.shields.io/gitlab/pipeline/harisekhon/Nagios-Plugin-Kafka?logo=gitlab&label=GitLab)](https://gitlab.com/HariSekhon/Nagios-Plugin-Kafka/pipelines)
[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-blue?logo=github)](https://github.com/HariSekhon/Nagios-Plugin-Kafka)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-blue?logo=gitlab)](https://gitlab.com/HariSekhon/Nagios-Plugin-Kafka)
[![Repo on BitBucket](https://img.shields.io/badge/repo-BitBucket-blue?logo=bitbucket)](https://bitbucket.org/HariSekhon/Nagios-Plugin-Kafka)

[![CI Mac](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Mac/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Mac%22)
[![CI Ubuntu](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Ubuntu/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Ubuntu%22)
[![CI Ubuntu 16.04](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Ubuntu%2016.04/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Ubuntu+16.04%22)
[![CI Ubuntu 18.04](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Ubuntu%2018.04/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Ubuntu+18.04%22)
[![CI Debian](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Debian/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Debian%22)
[![CI Debian 9](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Debian%209/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Debian+9%22)
[![CI Debian 10](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Debian%2010/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Debian+10%22)
[![CI CentOS](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20CentOS/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+CentOS%22)
[![CI CentOS 6](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20CentOS%206/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+CentOS+6%22)
[![CI CentOS 7](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20CentOS%207/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+CentOS+7%22)
[![CI CentOS 8](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20CentOS%208/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+CentOS+8%22)
[![CI Fedora](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Fedora/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Fedora%22)
[![CI Alpine](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Alpine/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Alpine%22)
[![CI Alpine 3](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Alpine%203/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Alpine+3%22)

[![CI Maven](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Maven/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Maven%22)
[![CI SBT](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20SBT/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+SBT%22)
[![CI Gradle](https://github.com/HariSekhon/Nagios-Plugin-Kafka/workflows/CI%20Gradle/badge.svg)](https://github.com/HariSekhon/Nagios-Plugin-Kafka/actions?query=workflow%3A%22CI+Gradle%22)

Kafka 0.9+ API CLI Tester & Advanced Nagios Plugin with Kerberos support, written in Scala.

Tested on Hortonworks HDP 2.4.0 with Kerberos + Ranger ACLs and Apache Kafka 0.8.x / 0.9.0.1 [docker images](https://hub.docker.com/r/harisekhon/kafka) with regular ACLs.

You may need to change the Kafka library version in `pom.xml` / `build.sbt` / `build.gradle` before building to match your deployed Kafka server / cluster otherwise it may hang when run due to version / protocol mismatch.
<!--
Testing shows it does take an extra second to negotiate the Kerberos authentication so make sure not to set ```--timeout``` to less than 2 secs if using Kerberos.
-->
See [The Advanced Nagios Plugins Collection](https://github.com/harisekhon/nagios-plugins#advanced-nagios-plugins-collection) for many more related enterprise monitoring programs.

Hari Sekhon

Cloud & Big Data Contractor, United Kingdom

(ex-Cloudera, former Hortonworks Consultant)

[https://www.linkedin.com/in/harisekhon](https://www.linkedin.com/in/harisekhon)
###### (you're welcome to connect with me on LinkedIn)

## Intro

This project builds a single self-contained Java jar file with all dependencies included and can simply be run on the command line with full switch option support:
```
java -jar check_kafka.jar --help
```

and there is an optional convenience shell wrapper script at the top level to make commands shorter:
```
./check_kafka --help
```

Run against one or more Kafka brokers, comma separated:
```
./check_kafka --brokers localhost:9092 --topic test
OK: Kafka broker successfully returned unique message via topic 'test' partition '0', write time = 0.185s, read time = 0.045s, total time = 1.729s | write_time=0.185s read_time=0.045s total_time=1.729s
```

Use the ```--verbose``` switch to also show the brokers list that were tested. If you have specified one of the kerberos switches (or edited the consumer/producer properties files to do so) then the output will additionally contain the marker ```with sasl authentication``` to let you know that it was a secure configuration that was tested (originally I called this ```with kerberos``` but technically it may not be in future).
```
OK: Kafka broker '<hortonworks_host>:6667' successfully returned unique message via topic 'topic3' partition '0' with sasl authentication, write time = 0.148s, read time = 0.043s, total time = 0.691s | write_time=0.148s read_time=0.043s total_time=0.691s
```

##### Kafka 0.9+ API Caveats

This program only supports Kafka 0.9+ as the API changed (again) and Kerberos security was only added in the 0.9 API. For Kafka versions before 0.9 you can find Python and Perl versions of this program in the [Advanced Nagios Plugins Collection](https://github.com/harisekhon/nagios-plugins#advanced-nagios-plugins-collection) that support 0.8 onwards (they dosn't support Kafka <= 0.7 as the API changed in 0.8 too and the underlying libraries in those languages don't support Kakfa <= 0.7).

It appears that several errors are caught too early in the new Kafka Java API and result in embedded looping retry behaviour on encountering errors (visible in debug level logging of the base library).

I haven't found a great way of handle that behaviour as it's not exposed to the client code so it ends up being handled via my generic default self timeout mechanism that I apply to all my tools. Hence if you specify an incorrect ```--brokers <host>:<port>``` or the Kafka brokers are down you or fail to negotiate the protocol due to security settings you will only receive a generic ```UNKNOWN: self timed out after 10 secs``` message as the code self terminates.

Otherwise the Kafka API would just hang there indefintely as it keeps retrying deeper in the library. I've tried various settings to get it to time out but nothing worked and I even posted to the Kafka users mailing list without answer. If you know of a setting that will make the Kafka Client library time out and return the more specific error then please let me know and I'll update this code accordingly.

#### Keberos Support

See the ```conf/``` directory for JAAS kerberos configurations.

If you're running the code on a Hortonworks Kafka broker it'll auto-detect the HDP configuration and use that.

### Build

#### Quick Start - Docker

A Dockerized pre-built version is available on [DockerHub](https://hub.docker.com/r/harisekhon/nagios-plugin-kafka).

If you have docker installed this one command will download and run it:
```
docker run harisekhon/nagios-plugin-kafka check_kafka --help
```

#### Automated Build from Source

Maven, Gradle and SBT automated builds are all provided.

A self-contained jar file with all dependencies will be created and symlinked to ```check_kafka.jar``` at the top level.

The Maven and Gradle builds are best as they will auto bootstap and run with no prior installed dependencies other than Java and ```make``` to kick it off.

The default ```make``` build will trigger a Gradle bootstrap from scratch with has an embedded checksum for security:

```
make
```

You can call any one of the 3 major build systems explicitly instead, which will recurse to build the library submodule using the same mechanism:

Maven:

```
make mvn
```

Gradle:

```
make gradle
```

SBT:

```
make sbt
```

##### Custom TLDs #####

If using bespoke internal domains such as `.local`, `.intranet`, `.vm`, `.cloud` etc. that aren't part of the official IANA TLD list then this is additionally supported via a custom configuration file [lib/resources/custom_tlds.txt](https://github.com/HariSekhon/lib-java/blob/master/src/main/resources/tlds-alpha-by-domain.txt) containing one TLD per line, with support for # comment prefixes. Just add your bespoke internal TLD to the file and it will then pass the host/domain/fqdn validations.

#### Testing

[Continuous Integration](https://travis-ci.org/HariSekhon/nagios-plugin-kafka) is run on this repo with tests for success and failure scenarios:
- unit tests for the custom supporting [java library](https://github.com/harisekhon/lib-java)
- integration tests of the top level programs using the libraries for things like option parsing
- [functional tests](https://github.com/HariSekhon/nagios-plugin-kafka/tree/master/tests) for the top level programs using [Docker containers](https://hub.docker.com/u/harisekhon/)

To trigger all tests run:

```
make test
```

which will start with the underlying libraries, then move on to top level integration tests and functional tests using docker containers if docker is available.

### Kafka 0.8 support - Alternative Perl & Python Kafka API Nagios Plugins

The [Advanced Nagios Plugins Collection](https://github.com/harisekhon/nagios-plugins#advanced-nagios-plugins-collection) has both Perl and Python predecessors to this program which work with Kafka 0.8+. The main differenitator with this Scala version is that it uses the new native 0.9+ Java API which has Kerberos support (the dynamic language versions were built on libraries for Kafka 0.8).

### See Also

* [DevOps Python Tools](https://github.com/harisekhon/devops-python-tools) - 80+ DevOps CLI tools for AWS, Hadoop, HBase, Spark, Log Anonymizer, Ambari Blueprints, AWS CloudFormation, Linux, Docker, Spark Data Converters & Validators (Avro / Parquet / JSON / CSV / INI / XML / YAML), Elasticsearch, Solr, Travis CI, Pig, IPython

* [The Advanced Nagios Plugins Collection](https://github.com/harisekhon/nagios-plugins) - 450+ programs for Nagios monitoring your Hadoop & NoSQL clusters. Covers every Hadoop vendor's management API and every major NoSQL technology (HBase, Cassandra, MongoDB, Elasticsearch, Solr, Riak, Redis etc.) as well as message queues (Kafka, RabbitMQ), continuous integration (Jenkins, Travis CI) and traditional infrastructure (SSL, Whois, DNS, Linux)

* [DevOps Bash Tools](https://github.com/harisekhon/devops-bash-tools) - 200+ DevOps Bash scripts, advanced `.bashrc`, `.vimrc`, `.screenrc`, `.tmux.conf`, `.toprc`, Utility Code Library used by CI and all my GitHub repos - includes code for AWS, Kubernetes, Kafka, Docker, Git, Code & build linting, package management for Linux / Mac / Perl / Python / Ruby / Golang, and lots more random goodies

* [DevOps Perl Tools](https://github.com/harisekhon/perl-tools) - 25+ DevOps CLI tools for Hadoop, HDFS, Hive, Solr/SolrCloud CLI, Log Anonymizer, Nginx stats & HTTP(S) URL watchers for load balanced web farms, Dockerfiles & SQL ReCaser (MySQL, PostgreSQL, AWS Redshift, Snowflake, Apache Drill, Hive, Impala, Cassandra CQL, Microsoft SQL Server, Oracle, Couchbase N1QL, Dockerfiles, Pig Latin, Neo4j, InfluxDB), Ambari FreeIPA Kerberos, Datameer, Linux...

* [HAProxy-configs](https://github.com/harisekhon/haproxy-configs) - 80+ HAProxy Configs for Hadoop, Big Data, NoSQL, Docker, Elasticsearch, SolrCloud, HBase, Cloudera, Hortonworks, MapR, MySQL, PostgreSQL, Apache Drill, Hive, Presto, Impala, ZooKeeper, OpenTSDB, InfluxDB, Prometheus, Kibana, Graphite, SSH, RabbitMQ, Redis, Riak, Rancher etc.

* [Dockerfiles](https://github.com/HariSekhon/Dockerfiles) - 50+ DockerHub public images for Docker & Kubernetes - Hadoop, Kafka, ZooKeeper, HBase, Cassandra, Solr, SolrCloud, Presto, Apache Drill, Nifi, Spark, Mesos, Consul, Riak, OpenTSDB, Jython, Advanced Nagios Plugins & DevOps Tools repos on Alpine, CentOS, Debian, Fedora, Ubuntu, Superset, H2O, Serf, Alluxio / Tachyon, FakeS3
