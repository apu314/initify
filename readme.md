<a align="center" href="http://cjpatoilo.com/initify"><img width="100%" src="http://cjpatoilo.com/initify/images/thumbnail.png" alt="The easy way to start open source projects."></a>

> The easy way to start open source projects.

[![Travis Status](https://travis-ci.org/cjpatoilo/initify.svg?branch=master)](https://travis-ci.org/cjpatoilo/initify?branch=master)
[![AppVeyor Status](https://ci.appveyor.com/api/projects/status/yd5ohn9syy91fk7l?svg=true)](https://ci.appveyor.com/project/cjpatoilo/initify)
[![Codacy Status](https://img.shields.io/codacy/grade/5009698540f040ec994a71fc84a4d675/master.svg)](https://www.codacy.com/app/cjpatoilo/initify/dashboard)
[![Dependencies Status](https://david-dm.org/cjpatoilo/initify/status.svg)](https://david-dm.org/cjpatoilo/initify)
[![Version Status](https://badge.fury.io/js/initify.svg)](https://www.npmjs.com/package/initify)
[![Download Status](https://img.shields.io/npm/dt/initify.svg)](https://www.npmjs.com/package/initify)
[![Gitter Chat](https://img.shields.io/badge/gitter-join_the_chat-4cc61e.svg)](https://gitter.im/cjpatoilo/initify)


## Why it's awesome

Initify is the easy way to start open source projects. Hope you enjoy!


## Install

**Install with npm**

```sh
$ npm install initify --global
```

**Install with Yarn**

```sh
$ yarn add initify
```


## Usage

```
	Usage:

		$ initify <directory> [<options>]

	Options:

		-h, --help              Display help information
		-v, --version           Output Initify version
		-l, --license           Set license
		-i, --ignore            Set .gitignore
		-c, --ci                Set continue
		--no-template           Disallow .github templates
		--no-editor             Disallow .editorconfig
		--no-readme             Disallow readme.md
		--no-license            Disallow license
		--no-ignore             Disallow .gitignore

	Examples:

		$ initify my-project
		$ initify sample --ignore android
		$ initify www --license apache-2.0

	Default when no arguments:

		$ initify <directory> --license mit --ignore node --ci travis
```


## Contributing

Want to contribute? Follow these [recommendations](https://github.com/cjpatoilo/initify/blob/master/.github/contributing.md).


## License

Designed with ♥ by [CJ Patoilo](http://twitter.com/cjpatoilo). Licensed under the [MIT License](http://cjpatoilo.mit-license.org).
