# The flags of all countries in the world in one sprite

Include 1 css file and have all the worlds' flags on your site. Tell everyone who uses a lot of country flags to use this link, so it will be in everyone's cache!

## Example usage:

In the head of your html file:

```html
<link
    rel="stylesheet"
    type="text/css"
    href="http://cloud.github.com/downloads/lafeber/world-flags-sprite/flags32.css"
/>
```

In the body of your html file:

```html
<ul class="f32">
  <li class="flag ar">Argentina</li>
  <li class="flag au">Australia</li>
  <li class="flag at">Austria</li>
  ...
</ul>
```

Included Currency-related flags, like:

```html
<ul class="f16">
  <li class="flag usd">USD</li>
  <li class="flag eur">EUR</li>
  <li class="flag chf">CHF</li>
  ...
</ul>
```

The countries corresponding to the codes can be found at: [http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)

If a previously visited site uses this same code, the file is already in the cache of the user and doesn't need to be downloaded again.
NB: It won't work in https environments. You can download the css files and include them locally instead.

See *the cheese wiki*: http://www.cheesewiki.com/ for an example
