Nearly-complete mirror of [phaser3-examples/…/assets](https://github.com/photonstorm/phaser3-examples/tree/master/public/assets). Most audio assets and a few large images were omitted.

Use
---

```javascript
this.load.crossOrigin = "anonymous";
this.load.setBaseURL("https://cdn.jsdelivr.net/gh/samme/phaser3-examples-assets@1.0.0/");
this.load.image("logo", "assets/sprites/phaser3-logo.png");
```

The first load of a fresh asset may be slow.
