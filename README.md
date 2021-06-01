# Using Zephyr for hard real-time applications: motor control

[![build](https://github.com/teslabs/spinner-zds-2021/actions/workflows/build.yml/badge.svg)](https://github.com/teslabs/spinner-zds-2021/actions/workflows/build.yml)
[![pdf](https://img.shields.io/badge/latest-pdf-blue)](https://github.com/teslabs/spinner-zds-2021/releases/latest)

This repository contains the sources for the talk "Using Zephyr for hard
real-time applications: motor control" presented at the 2021 Zephyr Developer
Summit.

## Build

The slides are written using the `beamer` LaTeX class. They can be built
by running:

```shell
make
```

Build files can be cleaned by running:

```shell
make clean
```

## Lint and format

Slides can be linted for errors by running:

```shell
make lint
```

Additionally, slides can be automatically formatted using:

```shell
make fmt
```
