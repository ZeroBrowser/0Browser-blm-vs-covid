# Headless-Puppeteer-Sample1

Using [0Browser](https://www.0browser.com)/Headless Browser + [Puppeteer](https://developers.google.com/web/tools/puppeteer) + [Google Vision API](https://cloud.google.com/vision) to analyse Corporate websites.

Find the full story [here](https://www.0browser.com/blogs/how-to-measure-corporate-america-reaction-to-blm-using-headless-browsers.html)

## Prerequisites
Get a free API Token from [0Borwser here](https://www.0browser.com/docs/get-token.html) 

## ⛏ Build

First, update browserWSEndpoint in puppeteerHelper.ts with your [0Browser](https://www.0browser.com) api token.

Then, open the terminal and run the following command to restore npm packages:

```
npm install
```

Build the Typescript application using this command:

```
npm run tsc
```

## 🏃 Run
Then, you can run the application using 

```
node .\out\index
```

Run it twice, once before change and once after change!

Enjoy! :wink:
