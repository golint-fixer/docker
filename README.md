# Docker

Docker is a library for the [Go Programming Language][go]. It provides some
operations to manage Docker containers.

## Status

[![Build Status](https://img.shields.io/travis/raiqub/docker/master.svg?style=flat&label=linux%20build)](https://travis-ci.org/raiqub/docker)
[![AppVeyor Build](https://img.shields.io/appveyor/ci/skarllot/docker/master.svg?style=flat&label=windows%20build)](https://ci.appveyor.com/project/skarllot/docker)
[![Coverage Status](https://coveralls.io/repos/raiqub/docker/badge.svg?branch=master&service=github)](https://coveralls.io/github/raiqub/docker?branch=master)
[![GoDoc](https://godoc.org/github.com/raiqub/docker?status.svg)](http://godoc.org/github.com/raiqub/docker)

## Features

 * **Container** type which provides commands to manage containers.
 * **Docker** type to manage Docker binary directly.
 * **Image** type which provides commands to manage images.
 * **ImageMongoDB** type which represents a MongoDB's Image.

## Installation

To install raiqub/docker library run the following command:

```bash
go get gopkg.in/raiqub/docker.v0
```

To import this package, add the following line to your code:

```bash
import "gopkg.in/raiqub/docker.v0"
```

## Examples

Examples can be found on [library documentation][doc].

## Running tests

The tests can be run via the provided Bash script:

```bash
./test.sh
```

## License

raiqub/docker is made available under the [Apache Version 2.0 License][license].


[go]: http://golang.org/
[doc]: http://godoc.org/github.com/raiqub/docker
[license]: http://www.apache.org/licenses/LICENSE-2.0
