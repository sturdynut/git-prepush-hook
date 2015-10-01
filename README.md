A really simple pre-push hook.

> This package is completely inspired by https://github.com/nlf/precommit-hook, thank you [NLF](https://github.com/nlf).

## Install
`npm install git-prepush-hook`

## Configuration

Configure the pre-push hooks via your `package.json`.

```javascript
{
  "name": "your_project",
  "description": "just an example",
  "scripts": {
    "test": "gulp test"
  },
  "pre-push": ["test"]
}
```

> Bugs or questions? [@sturdynut](http://twitter.com/sturdynut)

MIT License