# OpenTAXII

TAXII server implementation in Python from [EclecticIQ](https://www.eclecticiq.com).

OpenTAXII is a robust Python implementation of TAXII Services that
delivers rich feature set and friendly pythonic API built on top of well
designed application.

OpenTAXII is guaranteed to be compatible with [Cabby](https://github.com/EclecticIQ/cabby), TAXII client library.

[Source](https://github.com/EclecticIQ/OpenTAXII) | [Documentation](http://opentaxii.readthedocs.org) | [Information](http://www.eclecticiq.com) | [Download](https://pypi.python.org/pypi/opentaxii/)


[![Build Status](https://travis-ci.org/EclecticIQ/OpenTAXII.svg?branch=move_docs)](https://travis-ci.org/EclecticIQ/OpenTAXII)
[![Code Health](https://landscape.io/github/EclecticIQ/OpenTAXII/master/landscape.svg?style=flat)](https://landscape.io/github/EclecticIQ/OpenTAXII/master)
[![Coverage Status](https://coveralls.io/repos/EclecticIQ/OpenTAXII/badge.svg)](https://coveralls.io/r/EclecticIQ/OpenTAXII)
[![Documentation Status](https://readthedocs.org/projects/opentaxii/badge/?version=latest)](https://readthedocs.org/projects/opentaxii/)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Faukjan%2FOpenTAXII.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Faukjan%2FOpenTAXII?ref=badge_shield)


## Getting started
See [the documentation](https://opentaxii.readthedocs.org/en/latest/installation.html).

## Getting started with OpenTAXII using Docker

OpenTAXII can also be run using docker. This guide assumes that you have
access to a local or remote docker server, and won’t go into the setup
of docker.

To get a default (development) instance using docker

```bash
$ docker run -d -p 9000:9000 eclecticiq/opentaxii
```

> **NOTE:**
> OpenTAXII is now accessible through port 9000, with data stored
> locally in a SQLite database, and no authentication, using services defined
> in [services.yml](https://raw.githubusercontent.com/EclecticIQ/OpenTAXII/master/examples/services.yml) 
> and collections from [collections.yml](https://raw.githubusercontent.com/EclecticIQ/OpenTAXII/master/examples/collections.yml)

More documentation on running OpenTAXII in a container is found in the [OpenTAXII Docker Documentation](http://opentaxii.readthedocs.org/en/latest/docker.html).

## Feedback

You are encouraged to provide feedback by commenting on open issues or
sending us email at <opentaxii@eclecticiq.com>



## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Faukjan%2FOpenTAXII.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Faukjan%2FOpenTAXII?ref=badge_large)