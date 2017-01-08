# Modules Version Check

🔎 Check and automatically update local dependecies before your builds

* local modules check

![image](https://raw.githubusercontent.com/FrendEr/modules-version-check/master/static/mvc-demo1.gif)

* local modules check via `--match`

![image](https://raw.githubusercontent.com/FrendEr/modules-version-check/master/static/mvc-demo2.gif)

* update local modules

![image](https://raw.githubusercontent.com/FrendEr/modules-version-check/master/static/mvc-demo3.gif)

## Installation

```
npm install modules-version-check -g
```

## Help

```
Usage: modules-version-check [options] [command]


Commands:

  update   update local modules

Options:

  -h, --help        output usage information
  -v --version      output the version number
  --match <regexp>  regular expression matching
```

## Usage

```
cd your-project/

modules-version-check
```

## With task runner

#### [Gulp](https://github.com/FrendEr/gulp-modules-version-check)

* `npm install gulp-modules-version-check`

#### [Grunt](https://github.com/FrendEr/grunt-modules-version-check)

* `npm install grunt-modules-version-check`
