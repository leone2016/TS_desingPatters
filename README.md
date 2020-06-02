# Installing TypeScript compiler

```Consola
$ node -v

v.6.xx.x

$ npm -v 

6.xx.xx
```

> TypeScript compiler for Node.js is published as an npm package with command line
interface. To install the compiler, we can simply use the npm install command:

```Consola
$ npm install typescript -g

version  3.x.x

```

You may get a rough list of the options your TypeScript compiler provides
with switch -h. Taking a look into these options may help you discover
some useful features.

# Print out the legendary phrases

1.  Save the following code to file test.ts

```Ts

function hello(name: string): void {
    console.log(`hello, ${name}`);
}

hello('WORLD');
```
2. Change the following directory of your console to the folder containing the created file, and compile it with `tst:`

`$ tsc test.ts`

3. With luck, you should have the compiled javaScript file as **test.js**. Execute it with Node.js to get the ceremony done for
```Consola
$ node test.js

hello, world

```


