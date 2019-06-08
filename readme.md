# Architecture Builder Tools

## Quick Start

1. Write a template yaml file, for example:
``` yaml
- aws
  - vpc
    - subnet
        name: web subnet
        secerity-group: public
    - subnet
        name: database subnet
        secerity-group: private
```