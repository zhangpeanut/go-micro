# Go Micro [![License](https://img.shields.io/:license-apache-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![GoDoc](https://godoc.org/github.com/micro/go-micro?status.svg)](https://godoc.org/github.com/micro/go-micro) [![Travis CI](https://api.travis-ci.org/micro/go-micro.svg?branch=master)](https://travis-ci.org/micro/go-micro) [![Go Report Card](https://goreportcard.com/badge/micro/go-micro)](https://goreportcard.com/report/github.com/micro/go-micro)

Go Micro is a pluggable framework for distributed systems development.

## Overview

Go Micro provides the core requirements for distributed systems development including RPC and Event driven communication. 
The **micro** philosophy is sane defaults with a pluggable architecture. We provide defaults to get you started quickly 
but everything can be easily swapped out. 

<img src="https://micro.mu/docs/images/go-micro.png" />

Plugins are available at [github.com/micro/go-plugins](https://github.com/micro/go-plugins).

Follow us on [Twitter](https://twitter.com/microhq) or join the [Slack](http://slack.micro.mu/) community.

## Features

Go Micro abstracts away the details of distributed systems. Here are the main features.

- **Service Discovery** - Automatic service registration and name resolution (default: consul or mdns)
- **Load Balancing** - Client side load balancing built on discovery (default: random hashed)
- **Message Encoding** - Dynamic encoding based on content-type (default: protobuf and json-rpc)
- **Sync Streaming** - RPC based request/response with support for bidirectional streaming (default: http/1.1 and http2)
- **Async Messaging** - Native pubsub messaging built in for event driven architectures (default: point to point http)

## Getting Started

See the [docs](https://micro.mu/docs/go-micro.html) for detailed information on the architecture, installation and use of go-micro.

## Sponsors

Sixt is an Enterprise Sponsor of Micro

<a href="https://micro.mu/blog/2016/04/25/announcing-sixt-sponsorship.html"><img src="https://micro.mu/sixt_logo.png" width=150px height="auto" /></a>

Become a sponsor by backing micro on [Patreon](https://www.patreon.com/microhq)
