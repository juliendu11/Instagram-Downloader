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
const instagram_download = require ('@juliendu11/instagram-downloader')

instagram_download.downloadMedia('[MEDIA]', '[PATH_TO_SAVE]')
````

## Dependencies

- [axios](https://www.npmjs.com/package/axios)