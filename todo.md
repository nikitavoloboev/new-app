- `template new` is failing because [picolate](https://github.com/fabiospampinato/picolate) that is used as templating engine fails on `style={{`
  - add a way to tell picolate to parse with custom starting and ending tags, so you could use triple braces or whatever else that doesn't conflict with nothing else, and then you would list those tags in the template.json file