---
layout: page
title: Navigation & Tools
project: Navigation & Tools
aside: Elastic patterns for a plethora of edge cases
img: /img/multi-select.gif
class: nav-tool shadow
type: project
---

## The Problem

> ”How do you build a flexible navigation while the road map is still being finalized?”

This is one of the questions UI/UX Services at EMC has been answering over the last 6 months. We were tasked with designing a bullet-proof information hierarchy and navigational structure for three ongoing applications with radically different feature-sets. In addition to that, the bootstrap these frameworks were being built into were consumed by various other organizations within EMC. How do you make useful toolsets for teams distributed across verticals and geography?

## Guiding Principles
Over three meetings, we presented research and reviewed the types of interactions and structures most common to EMC products.

![](/nav-and-tools/img/raptor-site-guide.png)

When research concluded, three unifying principles emerged out of the dialog to guide the following solutions.

- **Flexibility** - Because some feature’s complexity approaching that of stand-alone applications in other fields, extendibility became a key focus for our team.

- **Clutter-Free** - The actions and management of complex data flows also necessitated a toolset and navigation that was out of the way when not needed, providing users of all screen sizes (desktop and mobile) a distraction-free workspace.

- **Powerful** - “Power user” is an attribute of two of our three most common Personas, so a smart navigation that provided access to 2nd, 3rd and ancillary data points was also a must-have.

## Solutions

### Omni-Nav
We settled on an Omni-Navigational window, build out with each mini-application inside the main pain, as well as system Utilities.

The omni-search at the top works from an index of the entire site; you can access pages 2 or 3 levels deep within that single page, as well as Tags and Events thrown by the Application itself.

**Detail Shot** We spent an extra hour and a half adding hotkeys  for opening, searching and traversing the omni-panel. We had a lot of fun adding in these little details for the power user personas.

### Secondary Nav
The secondary navigation was actually the last piece of the puzzle we committed to. We iterated through 4 different approaches before we landed the final solution. The prototype below, coded by <a href="codepen.com/jasesmith">Jase Smith</a>was one of the tests we threw against the solution.

<div class="wide" markdown="0">
<p data-height="680" data-theme-id="light" data-slug-hash="RraJwJ" data-default-tab="result" data-user="jasesmith" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/jasesmith/pen/RraJwJ/">UI Concept: The Whale</a> by Jase (<a href="http://codepen.io/jasesmith">@jasesmith</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
</div>

### Action Bar

For actions, which could be taken on individual items, components within an item, or on multiple-items at once, we assembled a
<!-- {: .wide }
<span>Testing, this is a test, test cool.</span> <span> Testing 2.</span>
{: .block .wide } -->
