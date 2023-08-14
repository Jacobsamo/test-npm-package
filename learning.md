## Helpful resources

- https://www.freecodecamp.org/news/how-to-create-and-publish-your-first-npm-package/
- Adding a README to the project on NPM: Link
- Versioning of NPM packages: Link
- Private NPM packages: Link

## How to test the package

1. Run `npm link` in your package dir
2. Go to your testing space locally run `npm link <package name>` this will install it
3. require it or import it `const test = require('<package name>');` or `import test from '<package name>';`

## Publishing to npm

1. Run `npm login` and login into your account
2. `npm publish` for your package to go public
