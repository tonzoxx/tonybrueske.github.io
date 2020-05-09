---
layout: post
title:  "Style Editor"
date:   2020-04-17 12:21:05 -0400
categories: ux/ui
excerpt-seperator: <!--more-->
---
<div class="excerpt-pre-post">
  <p>UX / UI for stylizing a Digideck with css in a WYSIWYG setting</p>
  <img src="/assets/images/style-editor-1.png" alt="Image of Digideck's Color Palette">
</div>

<!--more-->


<h2>Background</h2>

Users with multiple different levels of design skills need to be able to modify the look and feel of their existing Digideck Master Style (theme). Our goal was to give them an organized listing of the styles they can change as well as an intuitive way to go about selecting, modifying and creating new "styles". 

Goals of the tool:
<ul>
<li>Selection Tool to create CSS selectors for users</li>
<li>Organized listing for users to modify existing styles via WYSIWYG inputs</li>
</ul>

<div class="spacer-line"></div>

<h3>Style Editor Main View</h3>

The idea for the view is to have a tool bar that users can modify CSS Selectors and CSS properties, while barely dealing with that CSS unless they want to. The Changes that the user makes will happen in real time with little buffer to give the same feel as changing a color in photoshop or similar. 

On the left side of the page is the Style Tool bar, this area contains:
<ul>
<li>Master Style Selector</li>
<li>Viewport Tool (this also generates a media query for the css added)</li>
<li>Show and Hide all, to allow for users to view base styling</li>
<li>Move to Top or Bottom Buttons</li>
<li>Search Bar that searches title and CSS selector</li>
<li>Style Listing (CSS selectors)</li>
<li>Selecton Tool, for filtering and adding new styles</li>
<li>Manual Style Add button</li>
</ul>

<img src="/assets/images/style-editor-1.png" alt="Image of Digideck's Style Editor">

<div class="spacer"></div>

<h3>Single Style View</h3>

Once a User enters the Style they'd like to change they'll be met with a similar but different tool bar that will contain any existing styles with inputs to change. 

In this example the User clicked on the Lower Header Text Style and is presentated with the font-size and the color of the text. The user can then use those inputs to customize the look and feel of that item. 

<img src="/assets/images/style-editor-2.png" alt="Image of Digideck's Single Style Editor with a GUI">