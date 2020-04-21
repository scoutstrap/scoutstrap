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

To be tested and written


<!-- Skip the download with [BootstrapCDN](https://www.bootstrapcdn.com/) to deliver cached version of Bootstrap's compiled CSS and JS to your project.

{{< highlight html >}}
<link rel="stylesheet" href="{{< param "cdn.css" >}}" integrity="{{< param "cdn.css_hash" >}}" crossorigin="anonymous">
<script src="{{< param "cdn.js" >}}" integrity="{{< param "cdn.js_hash" >}}" crossorigin="anonymous"></script>
{{< /highlight >}}

If you're using our compiled JavaScript, don't forget to include Popper.js, via a CDN preferably, before our JS.

{{< highlight html >}}
<script src="{{< param "cdn.popper" >}}" integrity="{{< param "cdn.popper_hash" >}}" crossorigin="anonymous"></script>
{{< /highlight >}} -->

## Package managers

To be tested & written

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
