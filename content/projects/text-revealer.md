---
title: "Text Revealer 🔎"
description: "Reveal deeper information about highlighted text on a web page. It creates a pop up with additional information about the text selected. Such as Wikipedia definitions, Dictionary definitions, and others."
date: 2023-11-15
---

<!-- <span id="badges">
  <img alt="Mozilla Add-on"
    src="https://img.shields.io/amo/v/{b5ca06cf-4c6e-40f6-b367-a20a6f2a15ee}">
  <img src="https://img.shields.io/amo/rating/{b5ca06cf-4c6e-40f6-b367-a20a6f2a15ee}" />
  <img src="https://img.shields.io/amo/dw/{b5ca06cf-4c6e-40f6-b367-a20a6f2a15ee}" />
  <img src="https://img.shields.io/amo/users/{b5ca06cf-4c6e-40f6-b367-a20a6f2a15ee}" />
  <img src="https://img.shields.io/github/license/datastring/firefox-telegram-in-sidebar" />
</span> -->

## Introduction

Firefox extension to reveal deeper information about highlighted text on a web page.  Creates a pop up with additional information about the text selected. When text is selected, a popover displays useful details about the text such as:

- Wikipedia entries
- Dictionary definition
- ...and more to come.

[Demo](https://jamigibbs.github.io/text-revealer-js/)

[![Get the Addon](firefox.png)](https://addons.mozilla.org/en-US/firefox/addon/text-revealer/)

There is also a [vanilla JS version](https://github.com/jamigibbs/text-revealer-js) available. The script for this extension is generated from that project so please report any issues on [that repo](https://github.com/jamigibbs/text-revealer-js/issues/new/choose) unless it's a Firefox Extension specific issue.

## Preview

<img src="preview.gif" alt="Preview" />

## Available Settings

After activating the extenion, settings are available by clicking the Text Revealer icon in your browser navigation bar and selecting "Options":

<img src="settings.png" alt="Settings" width=400 />

## Changes from Original

- Toggle
  - Shunk size
  - Changed color
- Popover
  - Removed selection background

## Acknowledgments

This is the Firefox port of [Text Revealer](https://github.com/jamigibbs/text-revealer-js) by [Jami Gibbs](https://github.com/jamigibbs/).

## License

Source code in this repository is available under the [MIT](LICENSE) license. You are free to use this code however you see fit. That said, some acknowledgement would be well received.
