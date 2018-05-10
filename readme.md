# Awesome Puppeteer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [puppeteer](https://developers.google.com/web/tools/puppeteer/) resources for controlling [headless](https://developers.google.com/web/updates/2017/04/headless-chrome) Chrome (or Chromium) over the [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/).

<p align="center">
  <img width="200" src="https://cdn.rawgit.com/transitive-bullshit/awesome-puppeteer/master/logo.png">
</p>


## Contents

- [Official](#official)
- [Packages](#packages)
- [Testing](#testing)
- [Services](#services)
- [Articles](#articles)


## Official

- [Homepage](https://developers.google.com/web/tools/puppeteer/) - Official homepage.
- [GitHub](https://github.com/GoogleChrome/puppeteer) - Official GitHub repository.
- [API](https://github.com/GoogleChrome/puppeteer/blob/master/docs/api.md) - Official API docs.
- [Playground](https://try-puppeteer.appspot.com/) - Hosted playground where you can experiment with Puppeteer.
- [FAQ](https://developers.google.com/web/tools/puppeteer/faq) - Official FAQ.
- [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/) - Chrome DevTools Protocol API Docs.


## Packages

- [puppeteer-email](https://github.com/transitive-bullshit/puppeteer-email) - Email automation driven by headless chrome.
- [puppeteer-email-cli](https://github.com/transitive-bullshit/puppeteer-email/tree/master/packages/puppeteer-email-cli) - CLI for email automation driven by headless chrome.
- [puppeteer-github](https://github.com/transitive-bullshit/puppeteer-github) - GitHub automation driven by headless chrome.
- [puppeteer-github-cli](https://github.com/transitive-bullshit/puppeteer-github-cli) - CLI for GitHub automation driven by headless chrome.
- [docker-puppeteer](https://github.com/alekzonder/docker-puppeteer) - Docker image with puppeteer installed.
- [puppeteer-deep](https://github.com/zhentaoo/puppeteer-deep) - Seems popular, though I'm not sure what it does (PR?).
- [puppeteer-explore](https://github.com/laispace/puppeteer-explore) - Utility library for puppeteer.
- [differencify](https://github.com/NimaSoroush/differencify) - Library for visual regression testing.


## Rendering and web scraping

- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome. Very popular.
- [Puppetron](https://github.com/cheeaun/puppetron) - Demo site that shows how to use Puppeteer and Headless Chrome to render pages. Inspired by [GoogleChrome/rendertron](https://github.com/GoogleChrome/rendertron).
- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Crawler that provides simple APIs to manipulate Headless Chrome and allows you to crawl dynamic websites.
- [puppeteer-renderer](https://github.com/zenato/puppeteer-renderer) - Generic web page renderer.
- [ReedD/crawler](https://github.com/ReedD/crawler) - BFS site crawler.
- [pupperender](https://github.com/LasaleFamine/pupperender) - Express middleware that renders PWAs for bots using puppeteer.
- [prerenderer](https://github.com/Tribex/prerenderer) - Framework-agnostic prerendering for sites and SPAs.
- [apify-js](https://github.com/apifytech/apify-js) - Generic crawler.


## Testing

- [jest-puppeteer](https://github.com/smooth-code/jest-puppeteer) - Run your tests using Jest & Puppeteer.
- [mocha-headless-chrome](https://github.com/direct-adv-interfaces/mocha-headless-chrome) - Run client-side mocha tests in the command line through Puppeteer.
- [angular-puppeteer-demo](https://github.com/Quramy/angular-puppeteer-demo) - Demos how to use Puppeteer in Karma.
- [expect-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/expect-puppeteer) - Assertion library for Puppeteer.
- [storybook-chrome-screenshot](https://github.com/tsuyoshiwada/storybook-chrome-screenshot) - Storybook addon to save screenshots of your stories via puppeteer. 📷
- [e2e](https://github.com/dollarshaveclub/e2e) - End-to-end testing.


## Services

- [url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) - Web page PDF rendering done right. Self-hosted service for rendering.
- [checkly](https://checklyhq.com) - Monitoring SaaS that uses Puppeteer to check availability and correctness of web pages and apps.
- [browserless](https://github.com/joelgriffith/browserless) - Headless Chrome as a service letting you execute Puppeteer scripts remotely. Provides a docker image with configuration for concurrency, launch arguments and more.
- [Puppeteer Sandbox](https://puppeteersandbox.com) - Puppeteer sandbox environment as a service. Runs Puppeteer scripts and allows saving and embedding them in external sites and markdown files.


## Examples

- [Official examples](https://github.com/GoogleChrome/puppeteer/tree/master/examples/) - Quality examples as part of the official puppeteer repo.
- [Official use case-driven examples](https://github.com/GoogleChromeLabs/puppeteer-examples) - More complex, high quality, use case-driven examples.
- [puppeteer-examples](https://github.com/checkly/puppeteer-examples) - Quality examples for real life use cases such as scraping web pages and common login scenarios.
- [puppeteer-samples](https://github.com/sweekson/puppeteer-samples) - Misc examples.
- [daily-signin](https://github.com/yidinghan/daily-signin) - Signin and control various chinese sites.
- [linkedin-autoaccept](https://github.com/MRdotB/linkedin-autoaccept) - Auto-accept invitations on linkedin.


## Articles

- [Headless Chrome: an answer to server-side rendering JS sites](https://developers.google.com/web/tools/puppeteer/articles/ssr) - By a member of the Google headless chrome team.
- [Getting started with Puppeteer and Chrome Headless for Web Scraping](https://medium.com/@e_mad_ehsan/getting-started-with-puppeteer-and-chrome-headless-for-web-scrapping-6bf5979dee3e) - Excellent article detailing how to automate GitHub login and scraping.
- [A Guide to Automating & Scraping the Web with JavaScript (Chrome + Puppeteer + Node JS)](https://codeburst.io/a-guide-to-automating-scraping-the-web-with-javascript-chrome-puppeteer-node-js-b18efb9e9921) - Excellent, thorough article.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Alternative Headless Chrome Projects.
- [What's the difference between Chromium and Chrome?](https://www.howtogeek.com/202825/what%E2%80%99s-the-difference-between-chromium-and-chrome/)


## Contribute

Contributions welcome! Please read the [contributing guideline](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Travis Fischer](https://github.com/transitive-bullshit) has waived all copyright and related or neighboring rights to this work.
