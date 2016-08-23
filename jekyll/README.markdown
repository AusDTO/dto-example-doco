# `<dash-separated-repo-name>`

![CircleCI build status](https://circleci.com/gh/AusDTO/gov-au-transitions-alpha.svg?style=shield)

`<dash-separated-repo-name>` is a collection of prototypes for how we could meet user needs under the `<name>` programme of works.

**No content in this repository represents final technology choices or commitments.**

## Background

Per the service design and [delivery guidelines](https://www.dto.gov.au/standard/service-design-and-delivery-process/), the purpose of Alpha is to:

> Test out your hypotheses by building prototypes in code to explore different ways you might be able to meet your users’ needs. Explore multiple ideas. Do user research to learn which approach works best and iterate your solution as you learn more.

The technology stack for Alpha supports these outcomes:

- Delivery teams can use simple tech to rapidly prototype and validate hypotheses.
- Delivery teams have confidence changes will be deployed without failure.

It's crucial during the Alpha phase that delivery teams can focus on exploring ideas, not battle technology. We want to focus on validating our hypotheses about user behaviour without committing to writing large chunks of code we will likely throw away.

We prototype with HTML, CSS, and JavaScript. To provide a little bit of structure to teams when building the Alpha, we use Jekyll (a static site generator) and deploy to [cloud.gov.au](http://docs.cloud.gov.au/).

Alpha is about sketching out how users interact with the system. There is no backend code written during Alpha. Any references to particular technologies are purely for prototyping purposes, to test a hypothesis. Any references to technology do not represent decisions, commitments, or implementation choices for building the actual system in the Beta and Live.

We typically throw away any code written between Alpha and Beta.

You can read more about the process on the [Alpha Service Handbook](http://ausdto.github.io/service-handbook/alpha/).

## Requirements

* [Ruby](https://www.ruby-lang.org/en/) - v2.3.1
* [Node](https://nodejs.org/en/) - v4.2.x + (LTS)
* [Bower](https://bower.io/) - `npm install -g bower`

## Setup

Set up environment & install dependencies:

```
$ bin/setup.sh
```

Serve site locally at [http://localhost:4000/](http://localhost:4000/)

```
$ bundle exec jekyll serve
```
