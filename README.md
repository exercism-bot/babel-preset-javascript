# @exercism/babel-preset-javascript

This is the shared [`babel`][web-babel] preset configuration used by the [JavaScript track][git-javascript]. [Shareable configs][web-shareable-configs] are designed to work with the `presets` and `plugins` feature of `.babelrc` configuration files. This means you can use the same configuration you're used to on [Exercism][web-exercism] in your on projects!

## Usage

To use the configuration, open your [babel configuration][web-babel-configuration] file, and add the following value to `presets`. For example, for JSON based configuration files:

```json
{
  "presets": ["@exercism/babel-preset-javascript"]
}
```

## Configuration

Find the configuration [here](index.js). It's goal is to enable babel's preset environment, and occasionally introduce experimental syntax before it becomes widely adopted (stage 3 and beyond, for those following TC39).

[git-javascript]: https://github.com/exercism/javascript
[web-babel]: https://babeljs.io
[web-babel-configuration]: https://babeljs.io/docs/en/config-files
[web-exercism]: https://exercism.org
[web-shareable-configs]: https://babeljs.io/docs/en/presets
