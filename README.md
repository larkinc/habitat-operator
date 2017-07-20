![travis] ![report]

# habitat-operator

## Usage

To run the `habitat-operator` outside of a Kubernetes cluster, run:

    operator --kubeconfig ~/.kube/config

## Contributing

### Dependency management

This project uses [go dep](https://github.com/golang/dep/) for dependency
management.

If you add, remove or change an import, run:

    dep ensure

[travis]: https://travis-ci.org/kinvolk/habitat-operator.svg?branch=master
[report]: https://goreportcard.com/badge/github.com/kinvolk/habitat-operator
