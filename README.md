# fluent-bit-tracee-integration
Example of providing eBPF output from Tracee to any Fluent Bit endpoint

## Usage

Running on Ubuntu 20.04 with `docker` and `docker-compose` installed:

```shell
$ git clone <this repo>
$ cd <dir>
$ docker-compose up
```

The whole stack should spin up and in a minute or so Grafana should start receiving data, you can log in as `admin:admin` at `http://localhost:3000`.
