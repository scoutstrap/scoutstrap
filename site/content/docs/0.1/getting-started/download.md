---
layout: docs
title: Download
description: Download a compiled CSS and JS package to get started, or include with a package manager!
group: getting-started
toc: false
---

## Compiled CSS and JS

Download ready-to-use compiled code for **Scoutstrap v{{< param current_version >}}** to easily drop into your project, which includes:

- Compiled and minified JavaScript plugins

This doesn't include documentation, source files, or any optional JavaScript dependencies like Popper.js.

<a href="{{< param "download.dist" >}}" class="btn btn-primary" onclick="ga('send', 'event', 'Getting started', 'Download', 'Download Bootstrap');">Download</a>


## Source files

Compile Bootstrap with your own asset pipeline by downloading our source Sass, JavaScript, and documentation files. This option requires some additional tooling:

- Sass compiler (Libsass or Ruby Sass is supported) for compiling your CSS.
- [Autoprefixer](https://github.com/postcss/autoprefixer) for CSS vendor prefixing

<a href="{{< param "download.source" >}}" class="btn btn-secondary" onclick="ga('send', 'event', 'Getting started', 'Download', 'Download source');">Download source</a>

## CDN

Save on the download and hosting the code yourself by including cached copies from the JSDeliver CDN. Simply include the below resources in your project.

{{< highlight html >}}
<!-- CSS -->
<link rel="stylesheet" href="{{< param "cdn.css" >}}" integrity="{{< param "cdn.css_hash" >}}" crossorigin="anonymous">

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900;1,400;1,600&display=swap" rel="stylesheet">

<!-- Javascript (optional, but required for some components) -->
<script src="{{< param "cdn.js" >}}" integrity="{{< param "cdn.js_hash" >}}" crossorigin="anonymous"></script>
<script src="{{< param "cdn.popper" >}}" integrity="{{< param "cdn.popper_hash" >}}" crossorigin="anonymous"></script>
{{< /highlight >}}

## Package managers

Not yet tested!

<!-- ### npm

Install Bootstrap in your Node.js powered apps with [the npm package](https://www.npmjs.com/package/bootstrap):

{{< highlight sh >}}
npm install bootstrap
{{< /highlight >}}

`const bootstrap = require('bootstrap')` or `import bootstrap from 'bootstrap'` will load all of Bootstrap's plugins onto a `bootstrap` object.
The `bootstrap` module itself exports all of our plugins. You can manually load Bootstrap's plugins individually by loading the `/js/dist/*.js` files under the package's top-level directory.

Bootstrap's `package.json` contains some additional metadata under the following keys:

- `sass` - path to Bootstrap's main [Sass](https://sass-lang.com/) source file
- `style` - path to Bootstrap's non-minified CSS that's been precompiled using the default settings (no customization)

### yarn

Install Bootstrap in your Node.js powered apps with [the yarn package](https://yarnpkg.com/en/package/bootstrap):

{{< highlight sh >}}
yarn add bootstrap
{{< /highlight >}}

### Composer

You can also install and manage Bootstrap's Sass and JavaScript using [Composer](https://getcomposer.org/):

{{< highlight sh >}}
composer require twbs/bootstrap:{{< param current_version >}}
{{< /highlight >}}

### NuGet

If you develop in .NET, you can also install and manage Bootstrap's [CSS](https://www.nuget.org/packages/bootstrap/) or [Sass](https://www.nuget.org/packages/bootstrap.sass/) and JavaScript using [NuGet](https://www.nuget.org/):

{{< highlight powershell >}}
Install-Package bootstrap
{{< /highlight >}}

{{< highlight powershell >}}
Install-Package bootstrap.sass
{{< /highlight >}} -->
