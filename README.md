# gemini-babel

[![Greenkeeper badge](https://badges.greenkeeper.io/researchgate/gemini-babel.svg)](https://greenkeeper.io/)

[Gemini](https://github.com/gemini-testing/gemini) plugin, which allows to use
[babel](https://babeljs.io/) for writing tests.

## Usage

In your `.gemini.yml`:

```yaml
system:
  plugins:
    babel:
       ## babel options
       presets: [...]
       ...
```

It will also pick `.babelrc` file if you have any.
