Similar to [Shuffle Images by Pete R](https://github.com/peachananr/shuffle-images) but Vanilla JS

Shuffle Images let you display and shuffle multiple images by moving cursor around or several other ways to trigger. This plugin is perfect for when you want to save space while allowing users to take a peak at what other images are related to the one displayed. It can also be used to create an interactive animation on multiple static images at once.

## Basic Usage

HTML Markup
```html
<div class="shuffle-me">
    <img src="images/1.jpg">
    <img src="images/2.jpg">
    <img src="images/3.jpg">
    ..
</div>
  ```

Make sure all the images you want to shuffle are wrapped within a container where we will call the function on.

Run js:
```js
const shuffle = new ShuffleImages({
   target: ".shuffle-me",
});
shuffle.init();
```

## Options

1. type: `imageMouseMove`, `imageHover`, `documentMouseMove`, `documentScroll`
2. mouseMoveTrigger:  50 // Interger, default 50
3. hoverTrigger:  100 // Interger, default 100
4. scrollTrigger:  100 // Interger, default 100

## For developer

```
npm i
npm run dev
npm run build
```