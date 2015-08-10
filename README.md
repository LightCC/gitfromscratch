# git from scratch

[![Published on gitbook](https://img.shields.io/badge/gitbook-read-ff69b4.svg)](https://www.gitbook.com/book/diffplug/gitfromscratch/details)
[![Join the chat at https://gitter.im/diffplug/gitfromscratch](https://img.shields.io/badge/gitter-live_chat-brightgreen.svg)](https://gitter.im/diffplug/gitfromscratch)
[![License](https://img.shields.io/badge/license-Apache-blue.svg)](https://tldrlegal.com/license/apache-license-2.0-(apache-2.0))

This repo contains the source for a [gitbook](https://www.gitbook.com/) which describes how to learn git from scratch.

* You can read this book at [gitfromscratch.com](http://www.gitfromscratch.com)
* You can subscribe to changes in this book at [gitbook.com](https://www.gitbook.com/book/diffplug/gitfromscratch/details)

## To edit this book locally

`gradlew buildDocs` will build it and `gradlew serveDocs` will serve it.

The production version on `gitfromscratch.com` is built by gitbooks' infrastructure, which uses the latest version.  The local build is stuck on 1.3.2, as shown in `package.json`.  Only known issue is that the local build uses README.md as the intro instead of INTRO.md.

## Acknowledgements

* Many thanks to Jozef Vilcek for his [gitbook gradle example](https://github.com/JozoVilcek/gitbook-example/blob/master/package.json).
* Many thanks to the Gitbook team for their fantastic product.
