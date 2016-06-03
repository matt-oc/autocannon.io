![logo]()
> HTTP benchmarking tool written in Node.js

## Autocannon
This repo contains the documentation website for [autocannon][]. This documentation is available at
[autocannon.io][] or can be run locally by cloning this repo and following the steps below.

## Run Locally
After cloning, you will need to get dependencies via npm:

```
npm i
```

Next simply build and serve to port `8000`,

```
npm run start

```

## Contributing
Autocannon and its docs are __open projects__ and encourage participation. If you feel you can help in
any way, be it with examples, extra testing, tutorials, or new features please be our guest.

Please make all content changes in the [/src/pages][] folder. All changes are built just before we
redeploy the site so you only need to include changes in your PR. Upon your PR being accepted your
changes will be deployed.

Please see our [contribute][] page for more information.

## License
Copyright Matteo Collina and other contributors, Licensed under [MIT][].

[MIT]: ./LICENSE
[/src/pages]: ./src/pages
[contribute]: ./src/pages/contribute/index.md
[autocannon]: https://www.npmjs.com/package/autocannon
[autocannon.io]: http://autocannon.io
[Metalsmith]: http://metalsmith.io
