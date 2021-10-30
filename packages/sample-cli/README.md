sample-cli
==========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/sample-cli.svg)](https://npmjs.org/package/sample-cli)
[![Downloads/week](https://img.shields.io/npm/dw/sample-cli.svg)](https://npmjs.org/package/sample-cli)
[![License](https://img.shields.io/npm/l/sample-cli.svg)](https://github.com/packages/sample-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g sample-cli
$ sample-cli COMMAND
running command...
$ sample-cli (-v|--version|version)
sample-cli/0.0.0 darwin-x64 node-v16.11.1
$ sample-cli --help [COMMAND]
USAGE
  $ sample-cli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`sample-cli hello [FILE]`](#sample-cli-hello-file)
* [`sample-cli help [COMMAND]`](#sample-cli-help-command)

## `sample-cli hello [FILE]`

describe the command here

```
USAGE
  $ sample-cli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ sample-cli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/packages/sample-cli/blob/v0.0.0/src/commands/hello.ts)_

## `sample-cli help [COMMAND]`

display help for sample-cli

```
USAGE
  $ sample-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
