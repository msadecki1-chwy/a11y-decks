# Accessibility Slide Decks

A collection of slide decks for Accessibility related talks at Chewy:

## Chewy Web Conference May 2024

* [Intro to WAI-ARIA](https://rawcdn.githack.com/msadecki1-chwy/a11y-decks/main/IntroARIA.html)
* [Live Regions and Off-Screen Text](https://rawcdn.githack.com/msadecki1-chwy/a11y-decks/main/liveregions.html)
* [Manual Accessibility Testing](https://rawcdn.githack.com/msadecki1-chwy/a11y-decks/main/manualtesting.html)
* [Intro to Screen Reader Testing (Mac Edition)](https://rawcdn.githack.com/msadecki1-chwy/a11y-decks/main/srtestingmac.html)
* [Intro to Screen Reader Testing (Windows Edition)](https://rawcdn.githack.com/msadecki1-chwy/a11y-decks/main/srtestingwin.html)

## Useful links referenced in these slide decks

### Intro to WAI-ARIA

* [ARIA Authoring Practices Guide](https://www.w3.org/WAI/ARIA/apg/patterns/)
* [ARIA in HTML](https://www.w3.org/TR/html-aria/)
* [List of Roles (MDN)](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles)
* [List of `aria-*`(MDN)](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes)
* [HTML Validator](https://validator.nu/)
* [aXe DevTools Accessibiilty Extention](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)
* [Accessible Names and Descriptions](https://chewyinc.atlassian.net/wiki/spaces/Pro/pages/1258455490/Accessible+Names+and+Descriptions)

### Live Regions and Off-Screen Text

* [Chirp SASS Docs for `visually-hidden`](https://www.chirp-web.info/sassdoc-chirp/a11y.html#a11y)
* [ARIA Live Regions on Confluence](https://chewyinc.atlassian.net/wiki/spaces/Pro/pages/55444006/ARIA+Live+Regions)

### Manual Accessibility Testing

* [aXe DevTools Accessibiilty Extention](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)
* [aXe DevTools error reference for Chewy](https://chewyinc.atlassian.net/wiki/spaces/a11ydoc/pages/2202174494/Accessibility+Testing+Error+Reference)
* [How to enable Keyboard navigation on Mac](https://chewyinc.atlassian.net/wiki/spaces/Pro/pages/123535782/Setting+up+your+Apple+device+for+accessibility+testing#Step-1---Enable-keyboard-navigation)
* [Forced Color Mode](https://chewyinc.atlassian.net/wiki/spaces/Pro/pages/2055050132/Forced+Color+Modes+e.g.+Windows+High+Contrast+Mode)
* [HeadingsMap Extension](https://chromewebstore.google.com/detail/headingsmap/flbjommegcjonpdmenkdiocclhjacmbi)
* [Landmarks Extension](https://chromewebstore.google.com/detail/landmark-navigation-via-k/ddpokpbjopmeeiiolheejjpkonlkklgp)
* [Skip to Headings and Landmarks Extension](https://chromewebstore.google.com/detail/skipto-landmarks-headings/fjkpbfcodhflpdildjbmdhhmcoplghgf)
* [Accessible Names and Descriptions](https://chewyinc.atlassian.net/wiki/spaces/Pro/pages/1258455490/Accessible+Names+and+Descriptions)

#### Live Expressions that are useful for Manual Accessibility Testing

```
document.activeElement();
```
```
const { default: accname } = await import('https://cdn.skypack.dev/accname');
accname.getAccessibleName(document.activeElement);
```

### Intro to Screen Reader Testing (Mac Edition)

* [How to enable Keyboard navigation on Mac](https://chewyinc.atlassian.net/wiki/spaces/Pro/pages/123535782/Setting+up+your+Apple+device+for+accessibility+testing#Step-1---Enable-keyboard-navigation)
* [Voiceover Quick Reference Guide](https://codoid.com/accessibility-testing/a-voiceover-quick-reference-guide-with-keyboard-shortcuts-gestures/)

### Intro to Screen Reader Testing (Windows Edition)

* [NVDA Download](https://www.nvaccess.org/download/)
* [NVDA Shortcut Keys](https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts#nvda-nvda_shortcut_keys)

