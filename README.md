# Time Passing Lambda Image

Netlify Lambda Function that calculates the distance from a given date and now in words. Display the text on a PNG image and returns in base64 encoded binary format.

## Why?

Intended to mimic GitHub Markdown font style for embedding some dynamic content inside a static text file.

## Usage by example

Embed the Markdown code below to get "_8 month ago_" text in my current moment.

```py
![07:31 25/05/2020](https://domain/path/ago?time=1590391860000
```

The `time` parameter is Epoch timestamp in milliseconds.

## Serverless Setup

Deploy the entire repository to Netlify.
