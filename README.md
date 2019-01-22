framer-x-cli
============

Framer X command line tools

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/framer-x-cli.svg)](https://npmjs.org/package/framer-x-cli)
[![CircleCI](https://circleci.com/gh/kyo504/framer-x-cli/tree/master.svg?style=shield)](https://circleci.com/gh/kyo504/framer-x-cli/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/framer-x-cli.svg)](https://npmjs.org/package/framer-x-cli)
[![License](https://img.shields.io/npm/l/framer-x-cli.svg)](https://github.com/kyo504/framer-x-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g framer-x-cli
$ framer-x-cli COMMAND
running command...
$ framer-x-cli (-v|--version|version)
framer-x-cli/0.0.3 darwin-x64 node-v10.15.0
$ framer-x-cli --help [COMMAND]
USAGE
  $ framer-x-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`framer-x-cli delete [FILE]`](#framer-x-cli-delete-file)
* [`framer-x-cli hello [FILE]`](#framer-x-cli-hello-file)
* [`framer-x-cli help [COMMAND]`](#framer-x-cli-help-command)
* [`framer-x-cli init [FILE]`](#framer-x-cli-init-file)

## `framer-x-cli delete [FILE]`

describe the command here

```
USAGE
  $ framer-x-cli delete [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/delete.ts](https://github.com/kyo504/framer-x-cli/blob/v0.0.3/src/commands/delete.ts)_

## `framer-x-cli hello [FILE]`

describe the command here

```
USAGE
  $ framer-x-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ framer-x-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/kyo504/framer-x-cli/blob/v0.0.3/src/commands/hello.ts)_

## `framer-x-cli help [COMMAND]`

display help for framer-x-cli

```
USAGE
  $ framer-x-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.4/src/commands/help.ts)_

## `framer-x-cli init [FILE]`

describe the command here

```
USAGE
  $ framer-x-cli init [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/init.ts](https://github.com/kyo504/framer-x-cli/blob/v0.0.3/src/commands/init.ts)_
<!-- commandsstop -->
