# What is Logstash?

Logstash is a tool that can be used to collect, process and forward events and log messages. Collection is accomplished via number of configurable input plugins including raw socket/packet communication, file tailing and several message bus clients. Once an input plugin has collected data it can be processed by any number of filters which modify and annotate the event data. Finally events are routed to output plugins which can forward the events to a variety of external programs including Elasticsearch, local files and several message bus implementations.

> [wikitech.wikimedia.org/wiki/Logstash](https://wikitech.wikimedia.org/wiki/Logstash)

%%LOGO%%

# How to use this image

## Start Logstash with commandline configuration

If you need to run logstash with configuration provided on the commandline, you can use the logstash image as follows:

```console
$ docker run -it --rm logstash logstash -e 'input { stdin { } } output { stdout { } }'
```

## Start Logstash with configuration file

If you need to run logstash with a configuration file, `logstash.conf`, that's located in your current directory, you can use the logstash image as follows:

```console
$ docker run -it --rm -v "$PWD":/config-dir logstash logstash -f /config-dir/logstash.conf
```
