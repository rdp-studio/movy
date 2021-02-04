---
layout: default
---

![logo](img/logo.png)

**rdpmovy.js** is an easy-to-use animation engine based on three.js and gsap.



![gallery](img/gallery.png)

## Prerequisite

Please also make sure your node version is 12.x

> Notice: ReferenceError: BigInt is not defined ，you should make sure your node version is 12.x.


## Getting Started

Assuming you have [node.js](https://nodejs.org/) installed on your computer, you can install movy.js simply by:

```sh
npm i -g rdpmovy
```

To run movy.js, enter the following command in your terminal:

```sh
movy
```

It will show a list of example animations in the `examples` folder.

![examples](img/examples.png)

To create your own animation, you can start a new javascript file. Following is a simple hello-world program for movy.js.

```js
import * as mo from "movy";

const t = mo
  .addText("movy.js is simple!", {
    scale: 1,
    color: "yellow",
  })
  .reveal();

mo.run();
```

Save the file as `hello.js`, then open the animation in the browser by

```sh
movy hello.js
```
