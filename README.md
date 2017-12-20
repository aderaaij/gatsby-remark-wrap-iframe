Wraps iframes or objects (e.g. embedded YouTube videos) within markdown files in
a div with the classname `gatsby-iframe-wrap`. If you want out-of-the-box responsive iframes, please checkout [gatsby-remark-repsonsive-iframe](https://www.npmjs.com/package/gatsby-remark-responsive-iframe) instead. 

## Install

`npm install --save gatsby-remark-wrap-iframe`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-transformer-remark`,
    options: {
      plugins: [`gatsby-remark-wrap-iframe`],
    },
  },
];
```
