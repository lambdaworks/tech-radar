# Motivation

At [LambdaWorks](https://lambdaworks.io/), we maintain a [Tech Radar](https://lambdaworks.github.io/tech-radar/)
to help our engineering teams align on technology choices.

## What is the Tech Radar?

The [LambdaWorks](https://lambdaworks.io/) Tech Radar is a list of technologies, complemented by an assessment result,
called _ring assignment_.
We use six rings with the following semantics:
* __ADOPT__: Technologies we have high confidence in to serve our purpose, also on a large scale.
             Low risk and recommended to be widely used.
* __TRIAL__: Technologies that we believe should be adopted in the future, and we have started to incorporate them,
             but we're yet to have serious usage experience with them before we would consider them a general recommendation.
* __ASSESS__: Technologies that we believe could be of value to us in the future, but we're still in a research and
             experimentation phase to assess whether our confidence in them is high enough to apply them on a project.
* __HOLD__: Technologies we have adopted in the past, and we have existing projects relying on them, we plan to keep
            using them on the existing projects, but we prefer not applying them on new projects.
* __PHASE OUT__: Technologies we have adopted in the past, and we have existing projects relying on them, but we've decided
                 to gradually reduce dependency on them.
* __OPT OUT__: Technologies that we've either concluded not to adopt based on assessment or we have adopted in the past and have phased out.

## Contributing

The technologies included in the radar are maintained in the `entries` json-array defined
in `/docs/config.json`, ordered in alphabetical order. If you wish to add a technology or change
the positioning of an existing one, please open a pull-request with a change to `entries`.

## Local Development

Install dependencies with yarn (or npm):

```
yarn 
```

Start a local dev server:

```
yarn start
```

Your default browser should automatically open and show the url
 
```
http://localhost:3000/
```

## Credits
This *Tech Radar* was created based on the open source [Zalando Tech Radar](https://github.com/zalando/tech-radar).
