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
$ npm install -g @localezze/cli
$ localezze COMMAND
running command...
$ localezze (-v|--version|version)
@localezze/cli/0.0.2 darwin-x64 node-v14.17.6
$ localezze --help [COMMAND]
USAGE
  $ localezze COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`localezze hello [FILE]`](#localezze-hello-file)
* [`localezze help [COMMAND]`](#localezze-help-command)

## `localezze hello [FILE]`

describe the command here

```
USAGE
  $ localezze hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ lokezze hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/projects/localezze/blob/v0.0.2/src/commands/hello.ts)_

## `localezze help [COMMAND]`

display help for localezze

```
USAGE
  $ localezze help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
