---
layout: post
title:  "Creating a New Color Palette"
date:   2020-04-18 12:21:06 -0400
categories: ux/ui
excerpt_separator: <!--more-->
permalink: ux/ui/color-palette/
---

<div class="excerpt-pre-post">
  <p>Desiging a new color picker to be utilized withing multiple areas of an Application</p>
  <img src="/assets/images/color-palette-1.png" alt="Image of Digideck's Color Palette">
</div>

<!--more-->

<h2>Background</h2>

There was a need within Digideck for users to select and save colors to be used within the Text Editor as well as the future built Design Center.

The original editor had only allowed for a single hex color, it was stored for the session of the page only. Our goal was to create a new library to store colors. Later the scope expanded to also add the ability to create gradients and use rgba. 

Goals of the Tool:

<ul>
<li>Library for Creating Colors for on Brand Customization</li>
<li>Upgrade and face lift existing color picker</li>
</ul>

<div class="spacer-line"></div>

<h3>New Workspace and Color Palette</h3>

As a business tool a seperate page seemed most expected in terms of a library for all the colors. The palette will eventually be available via the picker tool as well so having this a seperate space will allow for simple color creation as well as advance colors for theme building. 

This will also be the new standard for the other workspaces we plan to utilize for the future <a href="tonybrueske.com/ux/ui/design-center/">Design Center</a> we are building. 

<img src="/assets/images/color-palette-1.png" alt="Image of Digideck's Color Palette">
<img src="/assets/images/color-palette-2.png" alt="Image of Digideck's Color Palette with Colors">

<div class="spacer"></div>

<h3>Upgrading the Existing Color Picker</h3>

We wanted to continue to use the existing color picker but add more features to it. 

Feature set of :

<ul>
<li>Solid Color</li>
<li>Linear Gradients</li>
<li>Radial Gradients</li>
<li>Add rgba</li>
<li>Include Custom Swatches from Palette</li>
</ul>

<img src="/assets/images/color-palette-3.png" alt="Upgrading the Existing Color Picker">

<div class="spacer"></div>

<h3>Adding in New Functionality</h3>

Adding in the ability to create gradients was a completely new piece of functionality outside of the ability of the color picker we were using. We found a tool for gradients we could use and expand the capabilities of our current picker as it was set to work with any existing color picker.

<img src="/assets/images/color-palette-4.png" alt="Gradient Color Pickers">