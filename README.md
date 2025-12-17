# Pure CSS Hover-Based Content Switcher

A fully CSS-driven content switcher that uses hover states to toggle visibility — **no JavaScript required**.  
Originally created on CodePen and later transferred to GitHub: [View original CodePen](https://codepen.io/johnfullerroot/pen/jOZdpQV)

## Overview

This project implements an animated tabbed content switcher using **only HTML and CSS**, with a novel hover-based approach. Unlike the widely used checkbox/radio hacks common online, this method:

- Allows content panels to switch **on hover**, no clicks required  
- Stacks all panels in the same position, hidden by default (`visibility: hidden; opacity: 0`)  
- Provides a sleeker, cleaner, and more fluid UI experience  

This approach demonstrates that state-like interface behavior can be achieved elegantly **without JavaScript** or form input tricks.

## Features

- Pure CSS, no JavaScript  
- Smooth hover-based animations  
- Easy to integrate into other projects  
- Lightweight and minimal  
- Works in all modern browsers  

## Usage

Open `index.html` in a browser.

## Why This is Unique

Most “pure CSS tabs” online rely on checkbox/radio input hacks. These have limitations:

- Require a click to switch tabs
- Keep a persistent state that can clutter the UI
- Depend on careful label/input pairing and DOM order

This project’s hover-only method is simpler, faster, and more natural for previewing or switching content quickly.

## Viewing on Mobile

This demo is best viewed on mobile devices in **landscape orientation**.

In portrait mode, the menu items remain visible, but the content panel extends beyond the viewport and requires horizontal scrolling. This is a layout choice for the demo rather than a limitation of the technique itself.

## Background and Motivation

This project originated from frustration with the common pure-CSS tab implementations that rely on hidden checkbox or radio input hacks.

While experimenting with CSS animations and hover-driven UI effects, it became clear that content visibility could be controlled directly through animated hover states — without introducing artificial form elements. The result is a simpler, more fluid approach to CSS-only content switching.

## Demo

Check out the live demo on GitHub Pages:  
[https://johnfullerroot.github.io/pure-css-hover-based-content-switcher/](https://johnfullerroot.github.io/pure-css-hover-based-content-switcher/)

## License
GPL-3.0-only
