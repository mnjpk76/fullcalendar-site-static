---
permalink: /reduced-test-cases
is_support: true
title: Reduced Test Cases
layout: text
custom_js: demo-to-codepen
---

## Step 1: Isolate the bug on your end

More often than not, the problem is with your code, not with FullCalendar. To determine this, remove as much of your code as possible:

- Remove all unrelated stylesheets and JS files
- Remove all unrelated 3rd party libraries
- Remove all server-side logic. Use static HTML and JSON files instead.

For more info on this technique, read [Reduced Test Cases](http://css-tricks.com/reduced-test-cases/).


## Step 2: Post a public demonstration of the bug

Use a service like [Codepen](http://codepen.io/) or [JSFiddle](http://jsfiddle.net/) to demonstrate the bug online. Enter your JS, CSS, HTML, and JSON and wire up all the relevant dependencies (jQuery, Moment, etc). To help you get started, here are some **debugging templates:**

<div style='margin:2em 0 2em 2em'>
  <div style='font-weight:bold'>FullCalendar Standard</div>
  <div style='margin-top:.5em'>
    <a data-codepen='{{ site.baseurl }}/docs/initialization-demo'>simple template</a> |
    <a data-codepen='{{ site.baseurl }}/docs/debug-json-feed'>JSON feed template</a>
  </div>
</div>

<div style='margin:2em 0 2em 2em'>
  <div style='font-weight:bold'>Scheduler Add-on</div>
  <div style='margin-top:.5em'>
    <a data-codepen='{{ site.baseurl }}/docs/timeline-standard-view-demo'>simple template</a> |
    <a data-codepen='{{ site.baseurl }}/docs/debug-scheduler-json-feed'>JSON feed template</a>
  </div>
</div>

*Instructions:* Make your changes, Click *Share* at the top, then get the *Link*.
