# Contributing to gnmi-netconf-adapter

More comprehensive documentation is available here:

- [Contributing to ONOS Project](https://docs.onosproject.org/developers/contributing/)
- [Developer Workflow](https://docs.onosproject.org/developers/dev_workflow/)

## Overriding the build variables

There are two options here;

- update the [.env file](../.env) with static values that are specific to your project
- use the --environment-overrides flag in make e.g. PRJ_VERSION=overridden make build --environment-overrides
