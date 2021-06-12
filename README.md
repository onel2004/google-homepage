# Google Homepage Clone

## Context

This is the first project I have had to do while taking The Odin Project course.
It consists in producing a clone of the google home page

## New knowledge

Basic search bar design
Fixed footer on page bottom

## Difficulties

I had difficulty at the bottom of the page

## Bugs

If I applied this :

```css
footer {
  position: fixed;
  bottom: 0;
}
```

this one does not work :

```css
footer .links-wrapper {
  display: flex;
  justify-content: space-between;
}
```

so I change it with this :

```css
footer .links-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
```

The result is still not what I expected.

## Languages

HTML, CSS

## Live preview

[Here](https://onel2004.github.io/google-homepage/)
