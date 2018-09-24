
# vault_lookup

A module to make it easier to fetch secrets from Hashicorp Vault from a Puppet agent. For example, to lookup the value of the `secret/test key` your Puppet code would be:

```$secret = Deferred('vault_lookup',["secret/test", 'http://vault.ourorg.tld:8200'])```

#### Table of Contents

1. [Description](#description)
2. [Setup - The basics of getting started with vault_lookup](#setup)
    * [What vault_lookup affects](#what-vault_lookup-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with vault_lookup](#beginning-with-vault_lookup)
3. [Usage - Configuration options and additional functionality](#usage)
4. [Limitations - OS compatibility, etc.](#limitations)
5. [Development - Guide for contributing to the module](#development)

## Description

For users with a puppet infrastructure looking to incorporate secret storage
with an existing Hashicorp Vault server.

## Setup

TBD.

### Beginning with vault_lookup

TBD.

## Usage

Install this module on your puppetserver installation; the necessary code will
distributed to puppet agents via pluginsync.

## Limitations

None.

## Development

TBD.

