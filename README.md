# Repair center

A workshop for [WOMEN WHO CODE Sydney](https://www.womenwhocode.com/sydney), which will be held on July 12th 2017.

[https://www.meetup.com/Women-Who-Code-Sydney/events/240653030/](https://www.meetup.com/Women-Who-Code-Sydney/events/240653030/).

## Requirements
* node `^5.10.0`
* yarn `^0.23.0` or npm `^3.0.0`
* Editor of your choice, preferably VSCode

> Only do the following if you don't have node and yarn installed
>
> ### Install homebrew
>
> ```bash
> $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
> ```
>
> ### Install node
>
> ```bash
> $ brew install nvm
> $ nvm install v6.8.1
> ```
>
> ### Install yarn
>
> ```bash
> $ brew install yarn
> ```
>
> ### Download VS Code
> [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
>

## Installation

```bash
$ git clone git@github.com:jchappypig/repair-center.git
$ cd repair-center
$ yarn
```

## Running the Project

```bash
$ yarn start
```

## Tutorial

### About

In this workshop, we will be using React and Redux to create web app for a repair center. Customer can visit the web app and log a ticket about the repairing devise, including its category, model and issue description.

### Requirements

The owner of the repair center has requested to build the web app with some sort of intelligence — based on what customer answered previously, the next set of questions should change dynamically.

Example flow is like this:

![Repair Center example flow](https://raw.githubusercontent.com/jchappypig/repair-center/master/src/assets/repair-center.png)


## Reference

* This project is build on top of boilerplate
[https://github.com/davezuko/react-redux-starter-kit](https://github.com/davezuko/react-redux-starter-kit)
