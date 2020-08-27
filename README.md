# Sizing images

## object-fit

- [MDN Object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)

Keep an eye on the browser compatibility section - currently IE has no support for this property.

## Manipulating images with imagemagick

Imagemagick has a collection of command line utilities that can do among many other things - resizing, compressing, changing image format from one to another.

```
# Resize all images in the current folder with the .jpg extension
mogrify -resize 50% *.jpg
```

- [Imagemagick](https://imagemagick.org/)
- [Mogrify](https://imagemagick.org/script/mogrify.php)

Note, that if you make the image really small, you cannot bring it back to a larger size with the level of detail it used to have. It might be good to keep a copy of the image as backup.

