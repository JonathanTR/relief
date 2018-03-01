# Reading on the internet can be painful

You ever sit down to read a long article, only to find your sight blurring and your brain shutting down due to the horrible formatting? I mean, historically speaking, [Project Gutenberg](https://www.gutenberg.org) is an incredible project, but try reading it for more than five minutes without inducing a migrain.

Fortunately, there are some very simple changes that can tame a wild bramble of text. This bookmarklet introduces three simple rules:

1.  Limit text width to 80 characters
2.  Set a readable line-height using the golden ratio
3.  Center the body text on the screen

The best part is, there is nothing to download. No dependencies other than your browser. In fact, here is all of the code necessary to change your life on the internet:

```javascript
function(){
  document.body.style.width = '80ch';
  document.body.style.lineHeight = '1.62em';
  document.body.style.margin = '0 auto';
}
```

Neat, huh? Through the magic of well-defined, open standards, you can comfortably read long form content on the internet again -- even if it was put there by some typographical neanderthal who gives not one damn about your eyesight and sanity.

All you need to do is drag this link to your bookmarks bar: [relief](javascript:(function(){document.body.style.width = '80ch';document.body.style.lineHeight = '1.62em';document.body.style.margin = '0 auto';})())
