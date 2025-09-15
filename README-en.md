# 🌲 Cypress, from Zero to the Cloud ☁️

Simple Project, developed for the TAT(Talikng About Testing) School Course


## Pre-requirements

You must have Git, Node.js and npm installed to clone and run the projetc.

> I used the following versions **22.17.0**, **10.9.2** and **2.50.0** of Node.js, npm and git, respectively. I recommend using the same or newer Long Term Support (LTS) versions of the listed systems.


## Instalation

* [Node.js](https://nodejs.org/en/download) (22.17.0 at the time of writing this article)
* npm (10.9.2 at the time of writing this article)
* [git](https://git-scm.com/) (2.50.0 at the time of writing this article)
> **Obs. :** When you install Node.js, npm is installed along with it.
> **Obs. 2:** To check the versions of Node.js, npm and git installed on your computer, run the command node `--version && npm --version && git --version` in your command line terminal.

## Tests

In this project, you can run the tests in desktop or mobile mode.


### Desktop

Run `npm test` ( or `npm t` for the short version) to run the test in headless mode on a desktop viewport.

Or, run `npm run cy:open` to open the Cypress App on a desktop viewport.

### Mobile

Run `npm run test:mobile` to run the test in headless mode on a mobile viewport.

Or, run `npm run cy:open:mobile` to open the Cypress App on a mobile viewport.

---

Project made with ♥ by [André Cavati](https://github.com/AndreCavati), with instruction from professor [Walmir Filho](https://github.com/wlsf82)