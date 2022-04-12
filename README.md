# The Illustrious Text Editor

This Illustrious Text Editor is a full-stack progressive web application that will allow users to store notes in their browser, whether online of offline.

# Description

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Table of Contents

- [License](#license)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Credits](#credits)
- [Tests](#tests)
- [Questions](#questions)
- [Contribute](#Contribute)

## License

[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

- Unlicensed

Refer to [https://choosealicense.com/](https://choosealicense.com/).

## Installation

To install this application, please follow the steps below:

1. In the integrated terminal, on the parent, client and server directories, run `npm i`
2. In the server terminal, run `node server.js`
3. Once the application starts, enter text into the Editor
4. Check the Application tab in the Dev Tools on Chrome. The text should be stored in `page-cache` in real time.
5. To see this application function offline, navigate to the Network tab in the Dev Tools on Chrome. At the top, change `No throttling` to `offline`. Reload the page and repeat Step 4. Notice the text is still updating in `page-cache`.

- EXTENSIONS:
  - webpack-dev-server
  - webpack-pwa-manifest
  - workbox-webpack-plugin

## Usage

- This applications uses Webpack Plugins to
- Demo:
- GitHub: https://github.com/smeske10/The-Illustrious-Text-Editor

![App Example]()
![Page-Cache Example]()

## Credits

- This application uses [Workbox Webpack Plugin](https://developer.chrome.com/docs/workbox/modules/workbox-webpack-plugin/) and [Webpack Inject Manifest](https://developer.chrome.com/docs/workbox/reference/workbox-build/#type-WebpackInjectManifestOptions) to create a progressive web application that can function online and offline by caching information in the browser.

## Questions

If you have any questions about the repo, open an issue or contact me directly at undefined. You can find more at [smeske10](https://github.com/smeske10/).

## Contribute

- Contact me directly at my GitHub

The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.
