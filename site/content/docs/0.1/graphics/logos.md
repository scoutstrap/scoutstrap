---
layout: docs
title: Logos
description: Pre-made Scout logos for inclusion in your designs, easily customised and re-sized.
group: graphics
aliases:
  - "/docs/0.1/logos/"
  - "/docs/logos/"
  - "/logos/"
toc: true
---

## Overview
We've taken the corporate logos and built them into the Scoutstrap styles to make it super easy to include in your designs without having to make loads of images. 

All you need to do is copy the below code and change the name to get a web friendly custom logo. Simple as that, no need for a logo generator!

## Inline Logo

The inline (horizontal) logo:

<p>
  <div class="logo-inline-black logo-inline-w250">
    <h6>1st Group</h6>
  </div>
</p>

{{< highlight html >}}
<div class="logo-inline-black logo-inline-w250">
  <h6>1st Group</h6>
</div> 
{{< /highlight >}}

## Stacked Logo

The stacked (horizontal) logo:
<p>
  <div class="logo-stacked-black logo-stacked-w150">
    <h6>1st Group</h6>
  </div>
</p>

{{< highlight html >}}
<div class="logo-stacked-black logo-stacked-w150">
  <h6>1st Group</h6>
</div> 
{{< /highlight >}}

## Colours
Logos can be re-coloured with helper classes as shown below. 

Note: in-line with brand guidelines we've deviated from the Bootstrap colour structure and only created classes for a subset of colours.

### Standard Colours

<p>
  <div class="d-inline-block p-3"><div class="logo-inline-black logo-inline-w200"> <h6>1st Group</h6> </div> </div>
  <div class="d-inline-block p-3"><div class="logo-inline-purple logo-inline-w200"> <h6>1st Group</h6> </div></div>
  <div class="rounded bg-dark d-inline-block p-3"><div class="logo-inline-white logo-inline-w200"> <h6>1st Group</h6> </div> </div>
</p>

{{< highlight html >}}
<div class="logo-inline-black logo-inline-w200"> <h6>1st Group</h6> </div>
<div class="logo-inline-purple logo-inline-w200"> <h6>1st Group</h6> </div>
<div class="logo-inline-white logo-inline-w200"> <h6>1st Group</h6> </div>
{{< /highlight >}}

<p>
  <div class="d-inline-block p-3"><div class="logo-stacked-black logo-stacked-w200"> <h6>1st Group</h6> </div> </div>
  <div class="d-inline-block p-3"><div class="logo-stacked-purple logo-stacked-w200"> <h6>1st Group</h6> </div></div>
  <div class="rounded bg-dark d-inline-block p-3"><div class="logo-stacked-white logo-stacked-w200"> <h6>1st Group</h6> </div> </div>
</p>

{{< highlight html >}}
<div class="logo-stacked-black logo-stacked-w200"> <h6>1st Group</h6> </div>
<div class="logo-stacked-purple logo-stacked-w200"> <h6>1st Group</h6> </div>
<div class="logo-stacked-white logo-stacked-w200"> <h6>1st Group</h6> </div>
{{< /highlight >}}

### Regional Colours

<p>
  <div class="d-inline-block p-3"><div class="logo-inline-red logo-inline-w200"> <h6>22nd Cardiff</h6> </div> </div>
  <div class="d-inline-block p-3"><div class="logo-inline-green logo-inline-w200"> <h6>81st Belfast</h6> </div></div>
  <div class=" d-inline-block p-3"><div class="logo-inline-blue logo-inline-w200"> <h6>23rd Aberdeen</h6> </div> </div>
</p>

{{< highlight html >}}
<div class="logo-inline-red logo-inline-w200"> <h6>22nd Cardiff</h6> </div>
<div class="logo-inline-green logo-inline-w200"> <h6>81st Belfast</h6> </div>
<div class="logo-inline-blue logo-inline-w200"> <h6>23rd Aberdeen</h6> </div>
{{< /highlight >}}

<p>
  <div class="d-inline-block p-3"><div class="logo-stacked-red logo-stacked-w200"> <h6>22nd Cardiff</h6> </div> </div>
  <div class="d-inline-block p-3"><div class="logo-stacked-green logo-stacked-w200"> <h6>81st Belfast</h6> </div></div>
  <div class="d-inline-block p-3"><div class="logo-stacked-blue logo-stacked-w200"> <h6>23rd Aberdeen</h6> </div> </div>
</p>

{{< highlight html >}}
<div class="logo-stacked-red logo-stacked-w200"> <h6>22nd Cardiff</h6> </div>
<div class="logo-stacked-green logo-stacked-w200"> <h6>81st Belfast</h6> </div>
<div class="logo-stacked-blue logo-stacked-w200"> <h6>23rd Aberdeen</h6> </div>
{{< /highlight >}}

## Sizing
Each of the logo types needs to be paired with a class to set it's width. We generate widths in 50px increments from 150 to 600px, which should hopefully meet most requirements.

### Inline Example
<p>
  <div class="logo-inline-black logo-inline-w150">
    <h6>1st Group</h6>
  </div>
  <br />
   <div class="logo-inline-black logo-inline-w200">
    <h6>1st Group</h6>
  </div>
  <br />
   <div class="logo-inline-black logo-inline-w250">
    <h6>1st Group</h6>
  </div>
  <br />
   <div class="logo-inline-black logo-inline-w300">
    <h6>1st Group</h6>
  </div>
  <br />
   <div class="logo-inline-black logo-inline-w350">
    <h6>1st Group</h6>
  </div>
  <br />
   <div class="logo-inline-black logo-inline-w400">
    <h6>1st Group</h6>
  </div>
</p>

{{< highlight html >}}
<!-- 150px wide -->
<div class="logo-inline-black logo-inline-w150"> <h6>1st Group</h6> </div> 
<!-- 200px wide -->
<div class="logo-inline-black logo-inline-w200"> <h6>1st Group</h6> </div> 
<!-- 250px wide -->
<div class="logo-inline-black logo-inline-w250"> <h6>1st Group</h6> </div> 
<!-- 300px wide -->
<div class="logo-inline-black logo-inline-w300"> <h6>1st Group</h6> </div> 
<!-- 350px wide -->
<div class="logo-inline-black logo-inline-w350"> <h6>1st Group</h6> </div>
<!-- 400px wide -->
<div class="logo-inline-black logo-inline-w400"> <h6>1st Group</h6> </div> 

<!-- 450+ ommited, use: logo-inline-w450, logo-inline-w500, logo-inline-w550, logo-inline-w600 -->
{{< /highlight >}}

### Stacked Example
<p>
  <div class="logo-stacked-black logo-stacked-w150">
    <h6>1st Group</h6>
  </div>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <div class="logo-stacked-black logo-stacked-w200">
    <h6>1st Group</h6>
  </div>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <div class="logo-stacked-black logo-stacked-w250">
    <h6>1st Group</h6>
  </div>

  <br />
   <div class="logo-stacked-black logo-stacked-w300">
    <h6>1st Group</h6>
  </div>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <div class="logo-stacked-black logo-stacked-w350">
    <h6>1st Group</h6>
  </div>
</p>

{{< highlight html >}}
<!-- 150px wide -->
<div class="logo-stacked-black logo-stacked-w150"> <h6>1st Group</h6> </div> 
<!-- 200px wide -->
<div class="logo-stacked-black logo-stacked-w200"> <h6>1st Group</h6> </div> 
<!-- 250px wide -->
<div class="logo-stacked-black logo-stacked-w250"> <h6>1st Group</h6> </div> 
<!-- 300px wide -->
<div class="logo-stacked-black logo-stacked-w300"> <h6>1st Group</h6> </div> 
<!-- 350px wide -->
<div class="logo-stacked-black logo-stacked-w350"> <h6>1st Group</h6> </div>

<!-- 400+ ommited, use: logo-stacked-w400, logo-stacked-w450, logo-stacked-w500, logo-stacked-w550, logo-stacked-w600 -->
{{< /highlight >}}