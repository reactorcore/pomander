# Pomander
> */pōˈmandər,ˈpōˌmandər/* (noun) -
> a ball or perforated container of sweet-smelling substances such as herbs and spices, placed in a closet, drawer, or codebase to perfume the air or (formerly) carried as a supposed protection against infection.

## System Requirements

You need a working copy of npm, the package manager that comes bundled with [Node.js](https://nodejs.org/en/).

Using npm, install ESLint:

```
npm install -g eslint
```

## Installation
Within a git repository, run the following command:
```sh
curl -s https://raw.githubusercontent.com/hackreactor-labs/pomander/master/bin/install | bash
```

## Usage
Pomander uses a pre-commit hook to run staged JavaScript files through ESLint before each commit.

[ESLint](http://eslint.org/) is a popular linter that checks your code for syntax and style errors. By default, ESLint only checks for syntax errors. To create a more robust rule-set, you need to [set up ESLint in your project](http://eslint.org/docs/user-guide/getting-started) 

To skip Pomander, commit with the `--no-verify` option.
