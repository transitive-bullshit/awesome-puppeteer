# Awesome Puppeteer [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [puppeteer](https://developers.google.com/web/tools/puppeteer/) resources for controlling [headless](https://developers.google.com/web/updates/2017/04/headless-chrome) Chrome (or Chromium) over the [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/).

<p align="center">
  <img width="200" src="https://cdn.rawgit.com/transitive-bullshit/awesome-puppeteer/master/logo.png">
</p>

- [![china](https://raw.githubusercontent.com/gosquared/flags/master/flags/flags/shiny/24/China.png) **中文/Chinese**](https://github.com/transitive-bullshit/awesome-puppeteer/blob/master/readme.zh.md)


## Contents

- [Official](#official)
- [Packages](#packages)
- [Rendering and web scraping](#rendering-and-web-scraping)
- [Testing](#testing)
- [Services](#services)
- [Examples](#examples)
- [Articles](#articles)
- [Related](#related)


## Official

- [Website](https://pptr.dev) - Official Website.
- [Homepage](https://developers.google.com/web/tools/puppeteer) - Official homepage.
- [GitHub](https://github.com/GoogleChrome/puppeteer) - Official GitHub repository.
- [API](https://github.com/GoogleChrome/puppeteer/blob/master/docs/api.md) - Official API docs.
- [Playground](https://try-puppeteer.appspot.com) - Hosted playground where you can experiment with Puppeteer.
- [FAQ](https://developers.google.com/web/tools/puppeteer/faq) - Official FAQ.
- [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/) - Chrome DevTools Protocol API Docs.


## Packages

- [puppeteer-lottie](https://github.com/transitive-bullshit/puppeteer-lottie) - Renders [Lottie](http://airbnb.io/lottie) animations via [Puppeteer](https://github.com/GoogleChrome/puppeteer) to **image**, **GIF** or **MP4**.
- [puppeteer-lottie-cli](https://github.com/transitive-bullshit/puppeteer-lottie-cli) - CLI for this [puppeteer-lottie](https://github.com/transitive-bullshit/puppeteer-lottie).
- [puppeteer-email](https://github.com/transitive-bullshit/puppeteer-email) - Email automation driven by headless chrome.
- [puppeteer-email-cli](https://github.com/transitive-bullshit/puppeteer-email/tree/master/packages/puppeteer-email-cli) - CLI for email automation driven by headless chrome.
- [puppeteer-instagram](https://github.com/transitive-bullshit/puppeteer-instagram) - Instagram automation driven by headless chrome.
- [puppeteer-instagram-cli](https://github.com/transitive-bullshit/puppeteer-instagram-cli) - CLI for Instagram automation driven by headless chrome.
- [puppeteer-github](https://github.com/transitive-bullshit/puppeteer-github) - GitHub automation driven by headless chrome.
- [puppeteer-github-cli](https://github.com/transitive-bullshit/puppeteer-github-cli) - CLI for GitHub automation driven by headless chrome.
- [puppeteer-social-image](https://github.com/chrisvxd/puppeteer-social-image) - Render social share images using HTML + CSS.
- [docker-puppeteer](https://github.com/alekzonder/docker-puppeteer) - Docker image with puppeteer installed.
- [puppeteer-explore](https://github.com/laispace/puppeteer-explore) - Utility library for puppeteer.
- [differencify](https://github.com/NimaSoroush/differencify) - Library for visual regression testing.
- [puppeteer-extra](https://github.com/berstend/puppeteer-extra) - Wrapper to use stealth mode, custom user prefs, etc.
- [puppeteer-theater](https://github.com/nicoandmee/puppeteer-theater) - Automation framework focused on simplifying advanced workflows and stealth.
- [puppeteer-render-text](https://github.com/transitive-bullshit/puppeteer-render-text) - Robust text renderer using headless chrome.
- [puppeteer-recorder](https://github.com/checkly/puppeteer-recorder) - Chrome extension that records your browser interactions and generates a Puppeteer script. 🔥
- [minimalcss](https://github.com/peterbe/minimalcss) - Extracts the minimal / critical CSS used in a set of URLs.
- [puppeteer-cluster](https://github.com/thomasdondorf/puppeteer-cluster) - Cluster management for puppeteer.
- [chrome-aws-lambda](https://github.com/alixaxel/chrome-aws-lambda) - Chromium binary compatible with AWS Lambda (kept up to date with puppeteer).
- [capture-website](https://github.com/sindresorhus/capture-website) - Capture screenshots of websites.
- [capture-website-cli](https://github.com/sindresorhus/capture-website-cli) - CLI to capture screenshots of websites.
- [facebook-birthday-cli](https://github.com/igniteram/facebook-birthday-cli) - Command Line Interface to list and wish your facebook friends.
- [timecut](https://github.com/tungs/timecut) - Record smooth movies of web pages with JavaScript animations.
- [timesnap](https://github.com/tungs/timesnap) - Take screenshots of web pages at smooth intervals.
- [pwa-asset-generator](https://github.com/onderceylan/pwa-asset-generator) - CLI to generate multi-platform PWA icons, splash screens and meta code based on web standards.
- [@cliqz/adblocker-puppeteer](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-puppeteer) - Efficient and flexible adblocker library to easily block ads and trackers.
- [browserless](https://browserless.js.org) – A puppeteer-like Node.js library for interacting with Headless production scenarios.
- [puppet-canvas](https://github.com/pshihn/puppet-canvas) - HTML5 Canvas implementation for Node.JS backed by Puppeteer.

## Rendering and web scraping

- [headless-chrome-crawler](https://github.com/yujiosaka/headless-chrome-crawler) - Distributed crawler powered by Headless Chrome.
- [decktape](https://github.com/astefanutti/decktape) - PDF exporter for HTML presentation frameworks.
- [Puppetron](https://github.com/cheeaun/puppetron) - Demo site that shows how to use Puppeteer and Headless Chrome to render pages. Inspired by [GoogleChrome/rendertron](https://github.com/GoogleChrome/rendertron).
- [puppeteer-renderer](https://github.com/zenato/puppeteer-renderer) - Generic web page renderer.
- [ReedD/crawler](https://github.com/ReedD/crawler) - BFS site crawler.
- [pupperender](https://github.com/LasaleFamine/pupperender) - Express middleware that renders PWAs for bots using puppeteer.
- [prerenderer](https://github.com/Tribex/prerenderer) - Framework-agnostic prerendering for sites and SPAs.
- [Apify SDK](https://github.com/apifytech/apify-js) - Scalable web crawling and scraping library. 🕷️
- [webgif](https://github.com/anishkny/webgif) - Easily generate animated GIFs from websites.
- [whatspup](https://github.com/sarfraznawaz2005/whatspup) - WhatsApp chat from commandline/console/cli.
- [Wbot](https://github.com/vasani-arpit/WBOT) - Configurable Whatsapp auto reply bot.


## Testing

- [jest-puppeteer](https://github.com/smooth-code/jest-puppeteer) - Run your tests using Jest & Puppeteer.
- [mocha-headless-chrome](https://github.com/direct-adv-interfaces/mocha-headless-chrome) - Run client-side mocha tests in the command line through Puppeteer.
- [angular-puppeteer-demo](https://github.com/Quramy/angular-puppeteer-demo) - Demos how to use Puppeteer in Karma.
- [expect-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/expect-puppeteer) - Assertion library for Puppeteer.
- [storybook-chrome-screenshot](https://github.com/tsuyoshiwada/storybook-chrome-screenshot) - Storybook addon to save screenshots of your stories via puppeteer.
- [e2e](https://github.com/dollarshaveclub/e2e) - End-to-end testing.
- [rize](https://github.com/g-plane/rize) - High-level, fluent and chainable API provided library for puppeteer.
- [mochify](https://github.com/mantoni/mochify.js) - TDD with Browserify, Mocha, Headless Chrome and WebDriver.
- [tupe](https://github.com/jl-/tupe) - A generic unit-testing runner for front-end.
- [puppetry](https://puppetry.app/) - Scriptless E2E test automation tool.
- [wendigo](https://github.com/angrykoala/wendigo) - Puppeteer wrapper to ease test development.

## Services

- [Puppeteer Sandbox](https://puppeteersandbox.com) - Puppeteer sandbox environment as a service. Runs Puppeteer scripts and allows saving and embedding them in external sites and markdown files.
- [checkly](https://checklyhq.com) - Monitoring SaaS that uses Puppeteer to check availability and correctness of web pages and apps.
- [url-to-pdf-api](https://github.com/alvarcarto/url-to-pdf-api) - Web page PDF rendering done right. Self-hosted service for rendering.
- [browserless](https://github.com/joelgriffith/browserless) - Headless Chrome as a service letting you execute Puppeteer scripts remotely.
- [FusionExport](https://www.fusioncharts.com/fusionexport) - Export dashboards or charts to PDF or images. Looks mature.
- [ProxyCrawl](https://proxycrawl.com) - Headless Chrome as a service.
- [microlink.io](https://microlink.io) – Turns any site into data.
- [HeadlessTesting](https://headlesstesting.com) – Headless Chrome testing with Puppeteer in the Cloud.


## Examples

- [Official examples](https://github.com/GoogleChrome/puppeteer/tree/master/examples/) - Quality examples as part of the official puppeteer repo.
- [Official use case-driven examples](https://github.com/GoogleChromeLabs/puppeteer-examples) - More complex, high quality, use case-driven examples.
- [puppeteer-examples](https://github.com/checkly/puppeteer-examples) - Quality examples for real life use cases such as scraping web pages and common login scenarios.
- [puppeteer-samples](https://github.com/sweekson/puppeteer-samples) - Misc examples.
- [daily-signin](https://github.com/yidinghan/daily-signin) - Signin and control various chinese sites.
- [linkedin-autoaccept](https://github.com/MRdotB/linkedin-autoaccept) - Auto-accept invitations on linkedin.
- [instagram-get-images](https://github.com/aofdev/instagram-get-images) - Instagram image scraper.
- [puppeteer-deep](https://github.com/zhentaoo/puppeteer-deep) - Demos on crawling, UI automation, trace API and so on.
- [html_to_pdf](https://github.com/chuongtrh/html_to_pdf) - Generate a simple invoice PDF from HTML.

## Articles

- [Headless Chrome: an answer to server-side rendering JS sites](https://developers.google.com/web/tools/puppeteer/articles/ssr) - By a member of the Google headless chrome team.
- [Getting started with Puppeteer and Chrome Headless for Web Scraping](https://medium.com/@e_mad_ehsan/getting-started-with-puppeteer-and-chrome-headless-for-web-scrapping-6bf5979dee3e) - Excellent article detailing how to automate GitHub login and scraping.
- [A Guide to Automating & Scraping the Web with JavaScript (Chrome + Puppeteer + Node JS)](https://codeburst.io/a-guide-to-automating-scraping-the-web-with-javascript-chrome-puppeteer-node-js-b18efb9e9921) - Excellent, thorough article.
- [Chromeless, Chrominator, Chromy, Navalia, Lambdium, GhostJS, AutoGCD](https://medium.com/@kensoh/chromeless-chrominator-chromy-navalia-lambdium-ghostjs-autogcd-ef34bcd26907) - Alternative Headless Chrome Projects.
- [What's the difference between Chromium and Chrome?](https://www.howtogeek.com/202825/what%E2%80%99s-the-difference-between-chromium-and-chrome/)
- [NodeJs Scraping with Puppeteer](https://learnscraping.com/nodejs-web-scraping-with-puppeteer/) - IMDB Scraping example.

## Related

- [puppeteer-sharp](https://github.com/kblok/puppeteer-sharp) - Port of Puppeteer to .NET.
- [foxr](https://github.com/deepsweet/foxr) - Node.js API to control Firefox. 🦊
- [pyppeteer](https://github.com/pyppeteer/pyppeteer) - Unofficial Python port of Puppeteer.
- [capybara-chrome](https://github.com/carezone/capybara-chrome) – Unofficial Ruby port of Puppeteer.


## Contribute

Contributions welcome! Please read the [contributing guideline](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Travis Fischer](https://github.com/transitive-bullshit) has waived all copyright and related or neighboring rights to this work.
