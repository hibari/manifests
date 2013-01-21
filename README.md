
# Repo Manifests for Hibari

This is the repository to store Repo manifests for Hibari. Repo is a
repository management tool and used by Hibari developers to manage
multiple Git repositories.


# What is Repo?

[Version Control with Repo and Git](http://source.android.com/source/version-control.html)


# Getting Started

Please read Downloading Hibari section of Hibari Application Developer Guide.

- [English Version](http://hibari.github.com/hibari-doc/hibari-app-developer-guide.en.html#downloading-hibari)
- [Japanese Version](http://hibari.github.com/hibari-doc/hibari-app-developer-guide.ja.html#downloading-hibari)


# Hibari Library Dependencies

## Hibari Core

- **gdss_admin**
- **gdss_brick**
- **cluster_info**
- **partition_detector**
- **congestion_watcher**
- **gmt_util**
- **riak_err** (forked from basho/riak_err)
- **meck** (forked from eproxus/meck)


## Hibari Erlang client

- **gdss_client**
- **gdss_brick**
- a few more **TODO**


## Hibari UBF and Thrift

- **gdss_ubf_proto**
- **ubf_thrift** (forked from ubf/ubf-thrift)
- **ubf** (forked from ubf/ubf)
- Hibari Erlang client
- Hibari Core


## Hibari S3

- **gdss_s3_proto**
- Hibari Erlang client
- Hibari Core


## Hibari JSON-RPC

- **gdss_json_rpc**
- **ubf_jsonrpc** (forked from ubf/ubf-jsonrpc)
- **mochiweb** (forked from mochi/mochiweb)
- Hibari UBF
- Hibari Erlang client
- Hibari Core


## Hibari-doc

- **asciiedoc** (forked from norton/asciidoc)
- **edown** (forked from esl/edown)


## Misc

- **s3**
- **rebar** (forked from basho/rebar)


# Notes on Third-party Libraries

- **ubf_jsonrpc** (fork) may be deleted
- **mochiweb** (fork)  may be deleted
- **rebar** (fork) may be deleted
