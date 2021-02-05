# Kitchen Sink [![renovate-app badge][renovate-badge]][renovate-app] [![semantic-release][semantic-image] ][semantic-url]

![kitchensink](https://cloud.githubusercontent.com/assets/1268976/14084252/e309e370-f4e7-11e5-9562-24f516563ac9.gif)
![LambdaTest Logo](https://www.lambdatest.com/images/logo.svg)

This is an example app used to showcase [Cypress.io](https://www.cypress.io/) testing. The application uses every API command in Cypress for demonstration purposes. Additionally this example app is configured to run tests in various CI platforms. The [tests](https://github.com/cypress-io/cypress-example-kitchensink/blob/master/cypress/integration/examples) are also heavily commented. For a full reference of our documentation, go to [docs.cypress.io](https://docs.cypress.io/).

To see the kitchen sink application, visit [example.cypress.io](https://example.cypress.io/).

[renovate-badge]: https://img.shields.io/badge/renovate-app-blue.svg
[renovate-app]: https://renovateapp.com/
[semantic-image]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-url]: https://github.com/semantic-release/semantic-release

## Help + Testing

**If you get stuck, here is more help:**

* [Gitter Chat](https://gitter.im/cypress-io/cypress)
* [Cypress Docs](https://on.cypress.io)

### 1. Fork this repo

If you want to experiment with running this project in Continous Integration, you'll need to [fork](https://github.com/cypress-io/cypress-example-kitchensink#fork-destination-box) it first.

After forking this project in `Github`, run these commands:

```bash
## clone this repo to a local directory
git clone https://github.com/<your-username>/cypress-example-kitchensink.git

## cd into the cloned repo
cd cypress-example-kitchensink

## install the node_modules
npm install && npm install -g lambdatest-cypress-cli

## generate LambdaTest Config
lambdatest-cypress init
```

**LambdaTest Authentication Credentials:** Make sure you have your LambdaTest credentials with you to run test automation scripts with Jest on LambdaTest Selenium Grid. You can obtain these credentials from the [LambdaTest Automation Dashboard](https://automation.lambdatest.com/) or through [LambdaTest Profile](https://accounts.lambdatest.com/detail/profile).

Set LambdaTest Username and Access Key in environment variables.

* For Linux/macOS:

    `export LT_USERNAME="YOUR_USERNAME"`

    `export LT_ACCESS_KEY="YOUR ACCESS KEY"`

* For Windows:

    `set LT_USERNAME="YOUR_USERNAME"`

    `set LT_ACCESS_KEY="YOUR ACCESS KEY"`

Edit `lambdatest-config.json` for desired os/browser combination and Specs location. 
please refer for [LambdaTest Capability Generator](https://www.lambdatest.com/capabilities-generator/) for list of available combination.


```bash
## launch the lambdatest-cypress test runner
lambdatest-cypress run
```
You'll get a link to LambdaTest Dashboard like `https://automation.lambdatest.com/logs/?build=xxxxx`
You should see the Kitchen Sink App up and running at lambdatest grid.

### 2. Install & write tests in Cypress

[Follow these instructions to install and write tests in Cypress.](https://on.cypress.io/installing-cypress)

## Contributing

Check out the [Contributing Guideline](/CONTRIBUTING.md).

## Changelog

- after v1.0.4 at [cypress-example-kitchensink/releases](https://github.com/cypress-io/cypress-example-kitchensink/releases)
- before at [CHANGELOG_OLD.md](CHANGELOG_OLD.md)
