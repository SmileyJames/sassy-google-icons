#Sassy Google Icons

A Sass function which generates the data uri of a google material design icon, for use as a background image.

```sass
.svg {
    background-image: icon-url("account-box", rgb(178, 197, 215));
}
```

```css
.svg {
  background-image: url('data:image/svg+xml;utf8,<svg fill="%23b2c5d7" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewbox="0 0 24 24"><path d="M3 5v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-14c0-1.1-.9-2-2-2h-14c-1.11 0-2 .9-2 2zm12 4c0 1.66-1.34 3-3 3s-3-1.34-3-3 1.34-3 3-3 3 1.34 3 3zm-9 8c0-2 4-3.1 6-3.1s6 1.1 6 3.1v1h-12v-1z"/><path d="M0 0h24v24h-24z" fill="none"/></svg>');
}

```

All icons used can be viewed at http://google.github.io/material-design-icons/

Use the name of the icon with spaces replaced by a hyphen("-").

```
label outline -> label-outline
```
If no colour is specified the fill will default to black.
