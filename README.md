lokezze
=======



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/lokezze.svg)](https://npmjs.org/package/lokezze)
[![Downloads/week](https://img.shields.io/npm/dw/lokezze.svg)](https://npmjs.org/package/lokezze)
[![License](https://img.shields.io/npm/l/lokezze.svg)](https://github.com/projects/lokezze/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g lokezze
$ lokezze COMMAND
running command...
$ lokezze (-v|--version|version)
lokezze/0.0.0 darwin-x64 node-v14.17.6
$ lokezze --help [COMMAND]
USAGE
  $ lokezze COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`lokezze hello [FILE]`](#lokezze-hello-file)
* [`lokezze help [COMMAND]`](#lokezze-help-command)

## `lokezze hello [FILE]`

describe the command here

```
USAGE
  $ lokezze hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ lokezze hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/projects/lokezze/blob/v0.0.0/src/commands/hello.ts)_

## `lokezze help [COMMAND]`

display help for lokezze

```
USAGE
  $ lokezze help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
