# Masscss

```bash
npm install masscss --save
```
```html
<link rel="stylesheet" href="node_modules/masscss/mass.css" />
```

or

```html
<link rel="stylesheet" href="https://unpkg.com/masscss/mass.css" />
```
---

Spiritual successor to [Basscss](https://basscss.com/), Masscss adopts all its classes (via [Ace.css](http://basscss.com/ace/)) and extends it with a massive amount of new classes.

No Sass, no variables, no fancy build workflow - it's just raw CSS.   

To use, simply link to mass.css in your page and use any of the thousands of classes included.

For production, use [uncss](https://github.com/uncss/uncss) to trim unused classes.

#### Extend/contribute

Clone your own copy of this repo, then `npm link` from said cloned repo and then `npm link masscss` (instead of  `npm install masscss`) to drop into your various projects.   

Then whenever you find yourself asking for a class that isn't already existing in masscss, create it in your cloned repo (following in the same declarative, functional, composable theme of the existing classes) and it will be immediately available  to your project.   

If you want later, submit a PR when you have a bunch of classes you would like to share / merge into mass.

---

Props to [jxnblk](https://github.com/jxnblk) for making Basscss and other cool projects and to all his influencers too.

MIT
