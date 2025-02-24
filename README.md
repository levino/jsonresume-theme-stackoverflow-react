# Yet another theme for json resume

> [!CAUTION]  
> This theme has been [integrated](https://github.com/jsonresume/jsonresume.org/tree/aa54dc2744d12edd1a33d39440dda0768030fefa/themes/stackoverflow) in the jsonresume monorepo. This also means that the name has [changed](https://www.npmjs.com/package/@jsonresume/theme-stackoverflow).


I made [`jsonresume-theme-stackoverflow-react`](https://www.npmjs.com/package/jsonresume-theme-stackoverflow-react) since I need to output a German CV in some cases. My package is a fork of [`jsonresume-theme-stackoverflow`](https://www.npmjs.com/package/jsonresume-theme-stackoverflow) which has a nice design. Maybe the people from this package will merge my changes in and then I will discontinue my fork. Please double check.

## Usage

Please also see my [demo repository](https://github.com/levino/demo-for-react-jsonresume-theme) for the usage of the multilangague feature. This package exports different theme generation scripts for different languages (currently German and English) in folders like `/dist/{LANGUAGE}/index.js` so once you have installed the package in your local project, you can do things like:

```
yarn resume export -r resume.de.json -t ./node_modules/jsonresume-theme-stackoverflow-react/dist/de CV.pdf
```

## Development

I made this as a basis for others to add more languages. The repo comes with a new stack (`react`) and new productivity tools (`storybook` and `i18next`) to ease the work. So I kindly invite you to open an issue for the new language you want to add and then make a PR providing support for that language.

## Previews

### Example CV

There is an automatic [deployment](https://stackoverflow-jsonresume-example.netlify.app/) of a made up example CV with this theme.

### Storybook deployment

There is an automatic storybook [deployment](https://sb-stackoverflow-jsonresume-theme.netlify.app/).

## Remarks

The CVs of Samantha Jones were made up / translated for me by ChatGPT. I also used ChatGPT to translate all handlebars templates to `jsx` code. Worked brilliantly and saved me so much time!
