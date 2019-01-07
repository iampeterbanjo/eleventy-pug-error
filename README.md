# Eleventy Pug error

MVP for errors when using front matter with Pug template using Eleventy static site generator as reported in [#358](https://github.com/11ty/eleventy/issues/358#issuecomment-451757868)

## Steps

* `npm install` and then `npm run test`
* Expected: Eleventy should compile pug template without errors
* Actual: Error is reported

```bash
> Having trouble rendering pug template ./list.pug (TemplateContentRenderError)
> Having trouble compiling template ./list.pug (TemplateContentCompileError)
> _includes:1:1
  > 1| /blog/
-------^

unexpected token "slash" (Error)
```

## Note

* Double quotes added [as suggested](https://github.com/11ty/eleventy/issues/358#issuecomment-451812070)
