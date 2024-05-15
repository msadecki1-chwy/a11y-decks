---
marp: true
paginate: true
author: Mark Sadecki
lang: en
title: Screen Reader Testing (Windows Edition)
keywords: Accessibility, Chewy, Chewy Web Conference, Talk, Screen Reader Testing 
---

<!-- _footer: <p>Use your arrow keys to navigate between slides</p> -->

# Screen Reader Testing (Windows Edition)

Chewy Web Conference Lighting Talk

May 8th, 2024

---
<style>section { font-size: 180%; } </style>

# What you'll need

- A Windows Computer
- NVDA <https://www.nvaccess.org/download/>
    - Chrome or Firefox
- Narrator
    - Edge
- Keyboard
- **EMPATHY**

---

# Fire it up!

- Open browser of choice
- Visit the page you want to test
- Double-click NVDA Icon or
    - CTRL + ALT + N turns on NVDA
    - CapsLock + Q turns off NVDA
- To Start Narrator, hit your Windows key and just type Narrator

*You may notice that when you start NVDA you are given some configuration options, the most important of which is what type of keyboard you are using, Laptop, or Desktop (full). Your choice will change the default "Bypass" key which we will learn more about later.*

---

# The Basics

- It's important to remember that screen reader users have no other choice but to use ONLY their keyboard, and only their screen reader, so if you find that you cannot access something (and you're sure it's not because you're not an expert SR user) it's a bug.  If you have to resort to your mouse to get passed something, or complete a task, its a bug.
- Screen reader function relies on just about every key on the keyboard, so in order to prevent the H key from typing an H, and using it to go to the next Heading instead, you have to combine it with the "Screen Reader", or "Bypass" key, which is different for every screen reder, but always configurable. The default for NVDA is CapsLock for Laptop configuration and Insert for Desktop.

---

# More Basics

- Screen Reader users have three modes of operation that they are constantly switching between:
    * Reading mode (Up and Down Arrow)
    * Interactive mode (Using just the TAB/Enter/Space/Arrow keys)
    * Quick Key Navigation (Advanced/Efficient, sometimes requires on NVDA Key)
    * Window's screen readers also have "Forms Processing" mode, but years ago it became standard to enable it automatically, so it's rarely used now.
* Try moving through the first two, and notice the different way the screen reader behaves

---

# Get more out of NVDA

- Enable NVDA Speech Viewer so you can see the speech queue on screen, inspect it, and even copy/paste.
    - NVDA System Tray icon (Windows + B) -> Tools -> Speech Viewer
- Use CTRL key at anytime to stop speech

---

# Quick Key Navigation

* List Navigation (NVDA + F7)
* Single Key Quick Nav is available unless in Forms processing mode. Try some popular ones:
    * H to move between headings
    * 2 to move between Level 2 headings
    * D to move between Landmarks
    * T to move between Tables

[Learn more about NVDA Shortcut Keys](https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts#nvda-nvda_shortcut_keys)

---

# What to look for

* While using your screen reader, imagine that the screen was completely blank.
    * Is the screen reader telling you everything you need to know to understand the purpose of the control?
        * It's type e.g. link, button, text field
        * It's label or name (its purpose or function)
        * The states or properties of that control (is there a popup, is it expanded or closed, are typeahead options available etc.)
    * Is the screen reader Presenting things to you in a logical order?
    * Can you access everything you would expect to access?
    * Is there redundant information that is annoying or cumbersome to navigate?

---

# What to do

If you find bugs, reach out to #accessibility-general Slack channel, me directly, or come to Accessibility Office Hours. There are so  many different options for optimizing and fixing the screen reader user experience.  Let's work together to figure that out.  

---

# Q&A