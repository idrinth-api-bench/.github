# Idrinth API Bench

| Tool |Version|
|-|-|
|Framework|[![npm version](https://badge.fury.io/js/@idrinth%2Fapi-bench.svg)](https://badge.fury.io/js/@idrinth%2Fapi-bench)|
|CLI|[![npm version](https://badge.fury.io/js/@idrinth%2Fapi-bench-cli.svg)](https://badge.fury.io/js/@idrinth%2Fapi-bench)|

This is the repository for the API test framework, it's CLI, it's
documentation website and other related tooling.

## Project parts

### [Framework](https://github.com/idrinth-api-bench/framework)

The framework is the core of the project. It is built without a framework
in Typescript and runs on Node.js.

### [CLI](https://github.com/idrinth-api-bench/cli)

This command line tool is free of frameworks and runs on Node.js. It
serves as a tool to generate code for use with the framework.

### [Desktop](https://github.com/idrinth-api-bench/desktop)

This vue and electron tool wraps the framework to provide a nicer,
easier to use UI for framework execution.

### [Documentation Website](https://github.com/idrinth-api-bench/documentation-website)

The documentation website is a React application written in Typescript.
It serves as the central web presence and documentation for all
involved projects.

### [Examples](https://github.com/idrinth-api-bench/examples)

These are examples based on @idrinth/api-bench (the framework). Try
them out to see how it works and what the framework provides.

### [History Microservice](https://github.com/idrinth-api-bench/history-microservice)

The history microservice is a Fastify application, that serves as
the central point of access to historical benchmark run data.

### [History Website](https://github.com/idrinth-api-bench/history-website)

The history website is a svelte application, that serves as
the central point of access to historical benchmark run data.

### [Containers](https://github.com/idrinth-api-bench/containers)

These are the docker containers for ci and history visualisation.

### [Mindmap](https://github.com/idrinth-api-bench/mindmap)

The brainstorming solution we use. It is based around markmap, a markdown to
mindmap generator but consists of a lot of custom logic.

### [Rollup Plugin React Modular CSS](https://github.com/idrinth-api-bench/rollup-plugin-react-modular-css)

This plugin extracts modular css files instead of creating a big one.

### [Chartjs Plugin Stdev Filler](https://github.com/idrinth-api-bench/chartjs-plugin-stdev-filler)

A small plugin to provide sensible standard deviation displays.

### [Website Builder](https://github.com/idrinth-api-bench/website-builder)

This repository is our website deploy and update tool to minimize github api queries.

### [Issues](https://github.com/idrinth-api-bench/issues)

This is the issue repository for a typescript framework meant to performance test anything even remotely rest-like and related tools.

### [Eslint Config](https://github.com/idrinth-api-bench/eslint-config)

The organisation's code standards.  

### [Typescript Language from Yaml](https://github.com/idrinth-api-bench/typescript-language-from-yaml)

A typescript solution for translations.

### [Assets](https://github.com/idrinth-api-bench/assets)

These are shared assets between multiple repositories.

### [Project Defaults](https://github.com/idrinth-api-bench/project-defaults)

These are the defaults of our projects, so make sure to use this for creating new repositories or updating existing ones.

### [Survey](https://github.com/idrinth-api-bench/survey)

A survey builder that focusses on being the least annoying to the surveyed as possible.

### [Duplicate Style Check](https://github.com/idrinth-api-bench/duplicate-style-check)

This small library checks media queries for duplicate style definitions.

### [React File Based Routes](https://github.com/idrinth-api-bench/react-file-based-routes)

File based routing with default react routers.

## Documentation

You can find the documentation on the
[Documentation Website](https://idrinth-api-ben.ch).
Additionally, we host the mindmap that assists the decision-making at the
[Mindmap Website](https://mindmap.idrinth-api-ben.ch).

## CI Images

We have ready-to-be-used CI Images:

- [Gitlab Runner](https://hub.docker.com/r/idrinth/api-bench-gitlab-runner)
- [Gitea Action](https://hub.docker.com/r/idrinth/api-bench-gitea-action)
- [Pure Alpine](https://hub.docker.com/r/idrinth/api-bench)

## Monitoring

We provide a monitoring solution out of the box.

- [Microservice](https://hub.docker.com/r/idrinth/api-bench-history-microservice)
- [Website](https://hub.docker.com/r/idrinth/api-bench-history-website)

## Setup

To get your project ready for development you need to run the following
commands in order:

- `git clone https://github.com/idrinth/api-bench`
- `cd api-bench`
- `npm run setup`

Further information about contributing is available in the contribution
guidelines [on the website](https://idrinth-api-ben.ch/contributing/).
## Socials

Please follow my socials to stay updated on the project:

[![idrinth Profile URL](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~idrinth)
[![LinkedIn URL](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/groups/9588634/)
[![Slack URL](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://idrinth-api-bench.slack.com/join/shared_invite/zt-2f4zmw2sz-c3etHzCFq3LtZpkR15xXMA#/shared-invite/email)

## Support

Commercial support and training is provided via
[Björn Büttner](https://bjoern-buettner.me).

## Privacy and Compliance

The `@idrinth/api-bench` framework and it's CLI do not collect any kind of
information about it's users or the API's being tested. All data is local to
the device you run it on or the database server you configure it to dump data
in.

## Feedback

If you have [Feedback](https://tally.so/r/3NA48l) you don't want to put into a discussion or issue, feel free to use the link.
