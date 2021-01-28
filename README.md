# Time Passing Lambda Image

[![Netlify Status](https://api.netlify.com/api/v1/badges/41464f3c-f6ff-48b7-a11e-d9fd7fae7fd0/deploy-status)](https://app.netlify.com/sites/time-passing/deploys)

Netlify Lambda Function that calculates the distance from a given date and now in words. Display the text on a PNG image and returns in base64 encoded binary format.

## Usage by example

Embed the Markdown code like this one below to get "_8 month ago_" text (in my current moment).

```py
![07:31 25/05/2020](https://domain/path/ago?time=1590391860000
```

:point_down: — :globe_with_meridians: Surely it's deployed and set real `domain/path` present LIVE example:

![07:31 25/05/2020](https://time-passing.netlify.app/.netlify/functions/ago?time=1590391860000)

:point_up: — :information_source: The `time` parameter is Epoch timestamp in milliseconds.


## Why?

Intended to mimic GitHub Markdown font style for embedding some dynamic content inside a static text file, especially in this progressing [GitHub Action](https://github.com/SubZtep/my-repos-action).

## Setup

Deploy the entire repository to somewhere server or serverless.
