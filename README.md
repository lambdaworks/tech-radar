# Motivation

At [LambdaWorks](https://lambdaworks.io/), we maintain a [Tech Radar](https://lambdaworks.github.io/tech-radar/)
to help our engineering teams align on technology choices.

## What is the Tech Radar?

The LambdaWorks Tech Radar is a list of technologies, complemented by an assessment result,called _ring assignment_.
We use six rings with the following semantics:
* __ADOPT__: Technologies we have high confidence in to serve our purpose, also in large scale.
             Low risk and recommended to be widely used.
* __TRIAL__: Technologies that we believe should be adopted in the future and we have started to incorporate them,
             but we're yet to have serious usage experience with them before we would consider them a general recommendation.
* __ASSESS__:Technologies that we believe could be of value to us in the future, but we're still in a research and
             experimentation phase to assess whether our confidence in them is high enough to apply them on a project.
* __HOLD__: Technologies we have adopted in the past and we have existing projects relying on them, we plan to keep
            using them on the existing projects, but we prefer not applying them on new projects.
* __PHASE OUT__: Techologies we have adopted in the past and we have existing projects relying on them, but we've decided
                 to gradually reduce dependency on them.
* __OPT OUT__: Techologies that we've either concluded not to adopt based on assessment or we have adopted in the past and have phased out.

## Contributing
The technologies included in the radar are maintained in the `entries` json-array defined
in `index.html`, ordered in alphabetical order. If you wish to add a techology or change
the positioning of an existing one, please open a pull-request with a change to `entries`.

## Local Development

1. install dependencies with yarn (or npm):

```
yarn 
```

2. start local dev server:

```
yarn start
```

3. your default browser should automatically open and show the url
 
```
http://localhost:3000/
```

## Credits
This Tech Radar was created based on the open source [Zalando tech radar](https://github.com/zalando/tech-radar).

## License

```
The MIT License (MIT)

Copyright (c) 2017 Zalando SE
Copyright (c) 2023 LambdaWorks

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

MIT License


```
