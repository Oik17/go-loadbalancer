# Go-LoadBalancer

## Overview
This project is a simple load balancer implemented in Go. It distributes incoming network traffic across multiple servers to ensure no single server becomes overwhelmed.

## Features
- Round-robin load balancing
- Health checks for backend servers
- Easy to configure and extend

## Installation
To install the dependencies, run:
```sh
go mod tidy
```

## Usage
To start the load balancer, run:
```sh
go run main.go
```
