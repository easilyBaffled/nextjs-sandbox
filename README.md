# Nextjs Sandbox

This is my space to play with the Nextjs sandbox and explore helpful tooling.

## Infra

- [ ] add `console.tap`
- [ ] define feature structure
- [ ] add `plop` file generator
- [ ] add linting & prettier

## Experiments

**PreBuilt Links**
If `<Link>` is used to navigate around the app, is there a way to get a list of all possible routes (all paths in `/pages`) and prebuild `Link` components that point to the given routes? eg:

```js
<Link.api.home /> -> <Link href="api/home">
<Link.home /> -> <Link href="/">
```

At the very least there should be exported constants for all of the paths, otherwise using strings for `href` will result in typos without errors.

- [ ] with plop read all of the routes in `/pages` and create files

## Fun

- [ ] add MDX

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/nextjs-kgydpm)
