# Playwright NodeJS - GitHub Actions Example
This repo contains samples for running [Playwright](https://playwright.dev/docs/intro) tests on BrowserStack using the browserstack-node-sdk through GitHub Actions.

<p float="left">
  <img src="https://static-00.iconduck.com/assets.00/browserstack-icon-1024x1024-7zz2pc78.png" width="100" height="110" title="BrowserStack" style="margin-right:50px;">
  <img src="https://seeklogo.com/images/G/github-actions-logo-031704BDC6-seeklogo.com.png" width="100" height="110" title="AdobeExpress">
</p>

## Setup

* Clone the repo `git clone https://github.com/garyb-bs/nodejs-playwright-gh-actions.git` and run `cd nodejs-playwright-gh-actions`.
* Set `BROWSERSTACK_USERNAME` and `BROWSERSTACK_ACCESS_KEY` as environment variables with your [BrowserStack Username and Access Key](https://www.browserstack.com/accounts/settings) or update the same in `browserstack.yml` file.
* Run `npm i` to install the dependencies.

## Running your tests

- To run the sample tests in parallel across the platforms specified in the `browserstack.yml`, run `npm run sample-test`.
- To run the sample local tests in parallel across the platforms specified in the `browserstack.yml`, run `npm run sample-local-test`.

## Notes
* You can view your test results on the [BrowserStack Automate dashboard](https://www.browserstack.com/automate)
* Understand how many parallel sessions you need by using our [Parallel Test Calculator](https://www.browserstack.com/automate/parallel-calculator?ref=github)
