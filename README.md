# auto-generate-ts-barrel

This is sample repository to generate typescript barrel automatically.

# Usage

```
$ yarn install
$ yarn watch
```

When you will create or change .ts(x) files.  
The `index.ts` file is created or updated as barrel in each directories.

```
$ touch src/components/Main.tsx
```

# Tools 

* [bencoveney/barrelsby](https://github.com/bencoveney/barrelsby)
* [kimmobrunfeldt/chokidar-cli](https://github.com/kimmobrunfeldt/chokidar-cli)

