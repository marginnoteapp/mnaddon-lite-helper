<h1 align="center" style="margin-top: 10px;">.mnaddon Lite Helper</h1>
<p align="center">
  <b>A helper for lite mnaddon development</b>
</p>

<p align="center">
  <a href="https://github.com/marginnoteapp/mnaddon-lite-helper/network/members"><img src="https://img.shields.io/github/forks/marginnoteapp/mnaddon-lite-helper.svg?style=flat" alt="forks"></a>
  <a href="https://github.com/marginnoteapp/mnaddon-lite-helper/stargazers"><img src="https://img.shields.io/github/stars/marginnoteapp/mnaddon-lite-helper.svg?style=flat" alt="stars"></a>
  <a href="https://github.com/marginnoteapp/mnaddon-lite-helper/blob/main/package.json"><img src="https://img.shields.io/badge/version-v1.0.1-orange" alt="version"></a>
  <a href="https://github.com/marginnoteapp/mnaddon-lite-helper/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" alt="license"></a>
</p>

## Usage
> ⚠️ Folders are not supported in a lite mnaddon projects.

> ⚠️ Only support Mac and Marginnote for Mac must be installed.
#### Install First
```shll
npm i mnaddon-lite -g
# Or Yarn
yarn add mnaddon-lite -g
# Or Pnpm
pnpm add mnaddon-lite -g
```
#### Then

You can use `mnaddon-lite help` or `mnaddon-lite help restart` to get more information.

```shll
Usage: mnaddon-lite command [options]
  $ mnaddon-lite create template
  $ mnaddon-lite resize ./logo.png -o new
  $ mnaddon-lite watch
  $ mnaddon-lite restart
  $ mnaddon-lite dev
  $ mnaddon-lite build
  $ mnaddon-lite unpack ./template.mnaddon -o output

Options:
  -v, --version                    output the current version
  -h, --help                       display help for command

Commands:
  create <project-name>            create a simple mnaddon project
  resize [options] <png-path>      resize logo to 44x44, which is required by MarginNote
  watch                            watch the file changes and copy changed file to the MarginNote extensition foler
  restart [options]                restart MarginNote and skip the unsign alert
  dev                              open MarginNote and Console, and then watch file changes
  build [output-name]              build a mnaddon file
  unpack [options] <mnaddon-path>  unpack a mnaddon file
  help [command]                   display help for command
```
## License

[MIT](https://github.com/marginnoteapp/mnaddon-lite-helper/blob/main/LICENSE)