# React via a CDN

This simple example shows how to use React via a CDN.

## Quick Start

```
npx serve .
```

This will serve the `index.html` file at http://localhost:3000.

## Summary

1. Reference React and ReactDOM via a CDN in the `<head>` of the HTML file.
2. Reference Babel via a CDN in the `<head>` of the HTML file. Babel compiles JSX into JavaScript, in the browser.
3. The React app's code is in the `<script type="text/babel">` tag. Babel looks for a script with this type, and compiles the code inside it. Babel converts the JSX into JavaScript.
