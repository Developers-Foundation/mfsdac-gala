## Required
Please download and install [Node](https://nodejs.org/en/) if you don't have it.

## Setup
After installing Node:

1) Open up console and move to the root directory of your local copy of this repo.

2) Run `npm install` to get website dependencies and wait for it to complete.

## Hosting the Website Locally
Run `gulp dev`, it should open up a new browser window with URL `http://localhost:3000`.

> Changing any of the HTML, LESS, Javascript, PHP or img files will automatically apply and update the browser!


> __NOTE__: To edit styles, please only modify the `custom.less` and the "custom" section of the `variables.less` files to avoid breaking the template's original styles.

If you accidentally close the browser/tab containing the website but still have `gulp dev` process running, you can reconnect to it by entering
the URL `http://localhost:3000` into your browser.
