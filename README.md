# Redis commander

Redis commander tool

[![Docker Build Status](https://img.shields.io/docker/build/sfoxdev/redis-commander.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/automated/sfoxdev/redis-commander.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/pulls/sfoxdev/redis-commander.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/stars/sfoxdev/redis-commander.svg?style=flat-square)]()

## Usage

### First run Redis server

### Run container
```
docker run -d --link my-redis:redis -p 8081:8081 sfoxdev/redis-commander --redis-host redis
```
