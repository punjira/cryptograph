# What this is

Cryptograph is a technical crypto market analyzer. The whole purpose of cryptograph is to find interesting opportunities in trading market. These signals are then categorized and delivered to users.  
This repo contains the code to all related services.  
this readme is getting updated

## Project overview

This project consists of several services each responsible for their related domain. Service communication is handled by [Nats streaming Server](https://github.com/nats-io/nats-streaming-server).  
To find candlestick patterns and calculate indicator values, the amazing [taLib](https://mrjbq7.github.io/ta-lib/) library is used.

## The Why

The Crypto market is growing fast and crypto traders with it. Anyone who has traded crypto immediately feels the need to look for several complex conditions in all crypto market which is an impossible task without necessary tools.
Also the combination of several conditions can filter the whole market to dozen of coins which can become really handy for scalpers and swingers.
Cryptograph aims to solve these complexities.

## The How

## Nats

## Services

## Development

## Running

clone the repo. cd into it and

```
docker-compose up --build
```

## Docker-Compose

## K8s

If you take look at k8s directory you will find couple of abandoned kubernetes deployment and service config files. This is because the project uses `docker-compose` thus the k8s config files are no longer developed or maintained. This is because running a kubernetes cluster requires a strong system config that costs a lot of money(more than my rent) and development with minikube is a nightmare on a machine with 8gbs of ram.

## Shared Modules

## Frontend

## Contribution

## Licence
