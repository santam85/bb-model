bb-model
========

Automate model tasks

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/bb-model.svg)](https://npmjs.org/package/bb-model)
[![Downloads/week](https://img.shields.io/npm/dw/bb-model.svg)](https://npmjs.org/package/bb-model)
[![License](https://img.shields.io/npm/l/bb-model.svg)](https://github.com/pet/bb-model/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g bb-model
$ bb-model COMMAND
running command...
$ bb-model (-v|--version|version)
bb-model/0.0.0 darwin-x64 node-v10.16.0
$ bb-model --help [COMMAND]
USAGE
  $ bb-model COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`bb-model hello [FILE]`](#bb-model-hello-file)
* [`bb-model help [COMMAND]`](#bb-model-help-command)
* [`bb-model sync`](#bb-model-sync)

## `bb-model hello [FILE]`

describe the command here

```
USAGE
  $ bb-model hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ bb-model hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/pet/bb-model/blob/v0.0.0/src/commands/hello.ts)_

## `bb-model help [COMMAND]`

display help for bb-model

```
USAGE
  $ bb-model help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.1/src/commands/help.ts)_

## `bb-model sync`

Syncronizes remote model with local

```
USAGE
  $ bb-model sync

OPTIONS
  --out-file=out-file                  [default: app-model]
  --portal-auth-path=portal-auth-path  [default: gateway/api/auth/login]
  --portal-context=portal-context      [default: gateway/api]
  --portal-host=portal-host            [default: localhost]
  --portal-name=portal-name            [default: retail-banking-demo-wc3]
  --portal-page-name=portal-page-name  [default: index]
  --portal-password=portal-password    [default: admin]
  --portal-port=portal-port            [default: 8080]
  --portal-protocol=(http|https)       [default: http]
  --portal-username=portal-username    [default: admin]

EXAMPLE
  $ bb-model sync --portal-name=<experience-name>
  model sync complete.
```

_See code: [src/commands/sync.ts](https://github.com/pet/bb-model/blob/v0.0.0/src/commands/sync.ts)_
<!-- commandsstop -->
