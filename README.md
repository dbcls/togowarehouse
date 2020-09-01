# TogoWarehouse

TogoWarehouse is a tool to serve linked data. This provides a set of components including RDF store, SPARQL query proxy server, and the other interface including GraphQL.

## Getting Started

Use `git clone --recursive https://github.com/inutano/togowarehouse` to clone this repository to fetch epBrowser submodule.

## Components

- [Virtuoso OpenSource](https://github.com/openlink/virtuoso-opensource): A RDF store
- [SPARQL proxy](https://github.com/dbcls/sparql-proxy): A proxy server for SPARQL endpoint
- [Grasp](https://github.com/dbcls/grasp): A GraphQL interface over SPARQL endpoint
- [nginx](https://nginx.org/)

## Usage

```
$ cd togowarehouse
$ mv /path/to/virtuoso.db ./db
$ docker-compose up -d
```
