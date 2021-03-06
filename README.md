hello-wasm directory:

Install wasm-pack in case don't have it
```
$ cargo install wasm-pack
```

Install node in case don't have it.

Building the package
```
$ wasm-pack build
```

Making our package available to npm:
```
$ cd pkg
$ npm link
```

Using the package on the web:
```
$ cd ../..
$ cd site
$ npm link hello-wasm
```

Update packages and run server:
```
$ npm install
$ npm run serve
```
