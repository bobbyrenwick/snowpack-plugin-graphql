# snowpack-plugin-graphql

This will allow you to use `.graphql` files with Snowpack, just like you can with `graphql-tag/loader` with webpack

It handles fragment imports like:

```
#import "./fragments.graphql"
```

# Usage

Install:
`yarn add snowpack-plugin-graphql`

In your snowpack config:

```
plugins: [
    ["snowpack-plugin-graphql"],
],
```
