# Storage-Schemas
 
## Badges

[![Build Status](https://dev.azure.com/EFSCIS/EFS-SDK/_apis/build/status/storage-schemas)](https://dev.azure.com/EFSCIS/EFS-SDK/_build/latest)

## Table of Contents

1. [About](#about)
2. [Getting Started](#getting_started)
3. [Usage](#usage)
4. [Deployment](#deployment)
5. [Built With](#built-with)
6. [Contributing](#contributing)
7. [Changelog](#changelog)
8. [Documentation](#documentation)
 
---
 
## About

Storage-Schemas is a model-definition-util. It provides models for organization- and space-events.
 
## Getting Started
 
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* jdk >= 11

### Installing

Execute the following steps to set up your local environment for development and testing:

- Clone the repository
 
## Usage

Commands that are required in order to use the service.

- <code>mvn generate-sources</code> to generate java-sources from avsc-files.

## Deployment

For deployment push the service to Azure DevOps, the pipeline will start automatically.

- <code>mvn deploy</code> to publish sources to maven repository.

## Built With

Links to tools used for building. Example:

- Maven v3.6.3 (see this [Link](https://maven.apache.org/))

## Contributing

See the [Contribution Guide](./CONTRIBUTING.md).

## Changelog
 
See the [Changelog](./CHANGELOG.md).
 
## Documentation

This package provides models for organizations and spaces as used in events. It can be used in all services publishing or consuming storage-events:

- accessmanager
- storagemanager
- orgspacemanager