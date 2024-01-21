# New App

> New Solid/Grafbase/EdgeDB/Tauri app

Uses:

- [Grafbase](https://grafbase.com/) for API
- [Solid](https://www.solidjs.com/) for web UI
- [Tauri](https://tauri.app/) and [Rust](https://www.rust-lang.org/) for desktop app
- [Hanko](https://www.hanko.io/) for authentication

Is used in production by [Learn Anything](https://github.com/learn-anything/learn-anything.xyz).

## Install

Clone this repo and:

```
cd template
pnpm i
```

Follow instructions in [template/readme.md](template/readme.md).

In future [template CLI](https://github.com/fabiospampinato/template) will be used to use the template more easily and automatically replace the variables inside the template with user defined ones. Things like `{{name}}` and `{{description}}` that you will see. For now replace them manually.

<!-- Install [template](https://github.com/fabiospampinato/template) by running:

```
npm install -g @fabiospampinato/template
```

Then run:

```
template install nikitavoloboev/new-app app
```

## Use template

```
template new app my-app
```

And fill in variables for the project like name, description.

After filling in values, you can `cd` into the project and read the `readme.md` for the setup instructions. -->

## Deploy template

Template is setup to be used with [Cloudflare Pages](https://pages.cloudflare.com/) as deploy target.

Push the template code to repository (private or public) and connect it in [Cloudflare Dashboard](https://dash.cloudflare.com).

It should automatically deploy the code and do so on every commit to `main` branch.

## More templates

Other templates can be seen [here](https://github.com/nikitavoloboev/new).

## Contribute

The tasks to do are outlined in [existing issues](../../issues) and in [tasks below](#tasks) (sorted by priority).

If issue/idea you have is not there, [open new issue](../../issues/new/choose) or [start discussion](../../discussions).

Any PR with code/doc improvements is welcome. ✨

Join [Discord](https://discord.com/invite/TVafwaD23d) for more indepth discussions on this repo and [others](https://github.com/nikitavoloboev#src).

## Tasks

- `template new` is failing because [picolate](https://github.com/fabiospampinato/picolate) that is used as templating engine fails on `style={{`
  - add a way to tell picolate to parse with custom starting and ending tags, so you could use triple braces or whatever else that doesn't conflict with nothing else, and then you would list those tags in the template.json file

### ♥️

[Support on GitHub](https://github.com/sponsors/nikitavoloboev) or look into [other projects](https://nikiv.dev/projects).

[![MIT](http://bit.ly/mitbadge)](https://choosealicense.com/licenses/mit/) [![Twitter](http://bit.ly/nikitatweet)](https://twitter.com/nikitavoloboev)
