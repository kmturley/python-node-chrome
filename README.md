# python-node-chrome

Docker image for sites which need to run:

* Python 2.7
* NodeJS 8.x
* Chrome

## Installation

    docker build -t "kmturley:python-node-chrome" .

## Usage

Within your own Dockerfile:

    FROM: kmturley/python-node-chrome

Within a CI pipeline:

    image: kmturley/python-node-chrome

## Contact

For more information please contact kmturley
