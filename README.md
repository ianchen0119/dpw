# dpw -- deno package watcher

![dpw-50](./images/dpw-50.png)

>  Notice: This tool is in an infancy development state.

## Purpose

This tool is designed to log every custom packages, be used in the project.

## How to use

### helper

```
dpw help
```

```
dpw -h
```

### Initial project

```
dpw init
```

```
dpw -i
```

Then, you'll see a new file, is called `import_map.json` is created in your project directory. 

### Use a custom package in the project

```
dpw use fmt
```

```
dpw -u fmt
```

Let's check the `import_map.json` in your project directory:

```
{
   "imports": {
      "fmt/": "https://deno.land/std@0.74.0/fmt"
   }
}
```

### Delete custom package in the project

```
dpw delete fmt
```

```
dpw -d fmt
```

## How to install

Sorry, this tool is in an infancy development state.

So, You can't get this tool now.