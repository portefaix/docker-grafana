# Portefaix Grafana

* Master :
[![Circle CI](https://circleci.com/gh/portefaix/docker-grafana/tree/master.svg?style=svg)](https://circleci.com/gh/portefaix/docker-grafana/tree/master)

* Develop :
[![Circle CI](https://circleci.com/gh/portefaix/docker-grafana/tree/develop.svg?style=svg)](https://circleci.com/gh/portefaix/docker-grafana/tree/develop)

![logo](https://raw.githubusercontent.com/1science/docker-alpine/latest/logo.png)

[Alpine Linux][] is a Linux distribution built around musl libc and BusyBox.
This image is based on the official Alpine Linux.

[Grafana][] is an open source, feature rich metrics dashboard and graph editor for
Graphite, InfluxDB & OpenTSDB

Port exported is : `3000`

Volumes exported are : `/var/lib/grafana`, `/var/log/grafana` and `/etc/grafana`

## Usage

    $ docker run --rm=true -it -p 3000:3000 portefaix/grafana

## Supported tags

- `2.0.2` [![](https://badge.imagelayers.io/portefaix/grafana:2.0.2.svg)](https://imagelayers.io/?images=portefaix/grafana:2.0.2 'imagelayers.io')
- `2.1.3` [![](https://badge.imagelayers.io/portefaix/grafana:2.1.3.svg)](https://imagelayers.io/?images=portefaix/grafana:2.1.3 'imagelayers.io')
- `2.5.0` [![](https://badge.imagelayers.io/portefaix/grafana:2.5.0.svg)](https://imagelayers.io/?images=portefaix/grafana:2.5.0 'imagelayers.io')
- `2.6.0` [![](https://badge.imagelayers.io/portefaix/grafana:2.6.0.svg)](https://imagelayers.io/?images=portefaix/grafana:2.6.0 'imagelayers.io')


## License

See [LICENSE](LICENSE) for the complete license.


## Changelog

A [ChangeLog.md](ChangeLog.md) is available.


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>


[Alpine Linux]: http://www.alpinelinux.org

[Grafana]: http://grafana.org/
