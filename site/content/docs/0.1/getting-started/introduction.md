---
layout: docs
title: Introduction
description: Getting started with Scoutstrap, the Scout themed bolt-on for Bootstrap.
group: getting-started
aliases:
  - "/docs/0.1/getting-started/"
  - "/docs/getting-started/"
  - "/getting-started/"
toc: false
---

 ## Quick start

To quickly add Scoutstrap use the hosted version provided by JSDelivr. Or if you want to reconfigure or host the files yourself, [head to the downloads page]({{< docsref "/getting-started/download" >}}.

If you're already using Bootstrap, just replace the standard Bootstrap CSS with the Scoutstrap CSS and make sure you've included the fonts. Scoutstrap is built ontop of the Bootstrap code, so includes all your favourite Bootstrap components!

### CSS

Copy-paste the stylesheet `<link>` into your `<head>` before all other stylesheets to load our CSS.

{{< highlight html >}}
<link rel="stylesheet" href="{{< param "cdn.css" >}}" integrity="{{< param "cdn.css_hash" >}}" crossorigin="anonymous">
{{< /highlight >}}

### Fonts

We need to include the Nunito Sans font. If you don't have a version, copy the below into your `<head>` to use a Google Fonts hosted copy.

{{< highlight html >}}
<link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900;1,400;1,600&display=swap" rel="stylesheet">
{{< /highlight >}}

### JS

Scoutstrap doesn't currently alter any of the standard Bootstrap JS. You can use thier copy, or copy the below to include the version based on the release Scoutstrap is built on (recommended!).

Place the following `<script>`s near the end of your pages, right before the closing `</body>` tag, to enable them. Popper.js must come first, and then our JavaScript plugins.

{{< highlight html >}}
<script src="{{< param "cdn.popper" >}}" integrity="{{< param "cdn.popper_hash" >}}" crossorigin="anonymous"></script>
<script src="{{< param "cdn.js" >}}" integrity="{{< param "cdn.js_hash" >}}" crossorigin="anonymous"></script>
{{< /highlight >}}


## Starter template

Be sure to have your pages set up with the latest design and development standards. That means using an HTML5 doctype and including a viewport meta tag for proper responsive behaviors. Put it all together and your pages should look like this:

{{< highlight html >}}
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="stylesheet" href="{{< param "cdn.css" >}}" integrity="{{< param "cdn.css_hash" >}}" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900;1,400;1,600&display=swap" rel="stylesheet">

    <title>Hello, Scouting World!</title>
  </head>
  <body>
    <h1>Hello, Scouting World!</h1>


    <script src="{{< param "cdn.popper" >}}" integrity="{{< param "cdn.popper_hash" >}}" crossorigin="anonymous"></script>
    <script src="{{< param "cdn.js" >}}" integrity="{{< param "cdn.js_hash" >}}" crossorigin="anonymous"></script>
  </body>
</html>
{{< /highlight >}}

That's all you need for overall page requirements. Visit the [Layout docs] or [our official examples]({{< docsref "/examples" >}}) to start laying out your site's content and components.