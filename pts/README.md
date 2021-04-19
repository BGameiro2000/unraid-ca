# Phoronix Test Suite docker template for Unraid

This repository contains the xml file with docker the template to add Phoronix Test Suite as a Community Application to Unraid.

## About the template

This template allows the installation of the Phoronix Test Suite as a docker container from Unraid's Community Application.
It contains the latest stable version.

There are also two path configuartions: the `/var/lib/phoronix-test-suite/` directory with the default `/mnt/user/appdata/phoronix-test-suite` and the optional path for `/var/lib/phoronix-test-suite/test-results`. In case the path for the backups isn't provided they will be present in `/mnt/user/appdata/phoronix-test-suite/test-results`. This definition is useful in case you want to setup a backup utility from the unraid pool and not the cache (where the `appdata` is stored).

## About PTS

Phoronix Test Suite is the most comprehensive testing and benchmarking platform available.

### Overview

The Phoronix Test Suite is the most comprehensive testing and benchmarking platform available that provides an extensible framework for which new tests can be easily added. The software is designed to effectively carry out both qualitative and quantitative benchmarks in a clean, reproducible, and easy-to-use manner. The Phoronix Test Suite can be used for simply comparing your computer's performance with your friends and colleagues or can be used within your organization for internal quality assurance purposes, hardware validation, and continuous integration / performance management.

### Links

- [Phoronix Test Suite website](https://www.phoronix-test-suite.com/)
- [Phoronix Test Suite github](https://github.com/phoronix-test-suite/phoronix-test-suite)
- [Phoronix Test Suite official docker](https://hub.docker.com/r/phoronix/pts/)
- [Phoronix Test Suite official documentation](https://www.phoronix-test-suite.com/documentation/)
- [Open Benchmarking website](https://openbenchmarking.org/)