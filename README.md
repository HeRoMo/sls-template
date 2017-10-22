# Serverless Framework template for AWS

This is a Serverless app framework for AWS.
This supports modern Javascript syntax, ex) async/await.

This uses the [serverless-webpack](https://www.npmjs.com/package/serverless-webpack) plugin and [Babel](https://babeljs.io/). It supports:

## Futures

- Modern Javascript syntax in your Lambda functions
  - ES2015 style syntax
  - support async/await

- Sourcemaps for proper error messages
  - Error message show the correct line numbers
  - Works in production with CloudWatch

- Support for multiple handler files
  - No need to add a new entry to your webpack.config.js

## Requirements
- Installing [Serverless Framework](https://serverless.com/)
- AWS credential

## Usage
Run the following command.<br>
You can create your serverless application, based on this template.

```bash
$ serverless install --url https://github.com/HeRoMo/sls-template --name your-app-name
$ cd your-app-name
$ yarn install
```

## License
MIT
