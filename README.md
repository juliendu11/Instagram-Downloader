[![Build Status](https://travis-ci.org/juliendu11/Instagram-Downloader.svg?branch=master)](https://travis-ci.org/juliendu11/Instagram-Downloader)

# Node JS Instagram downloader

Download Instagram images and videos (not api required)

It's async/await lib

Whenever you download a video, the preview will also be downloaded

## Install

```bash
npm i @juliendu11/instagram-downloader
```

# How to use ?

````javascript
const instagram_download = require ('@juliendu11/instagram-downloader');

(async () => {
const value = await instagram_download.downloadMedia('[MEDIA]', '[PATH_TO_SAVE]')
console.log(value)
})();

````

Example:


````javascript
const instagram_download = require ('@juliendu11/instagram-downloader');

(async () => {
const value = await instagram_download.downloadMedia('https://www.instagram.com/p/B_SgH6MHc2s/', './')
console.log(value)
})();
````

## Dependencies

- [axios](https://www.npmjs.com/package/axios)
