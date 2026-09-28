# Adding example media

1. Put selected media in `assets/cases/`.
2. In `index.html`, find `data-case-slot="image-01"` or `data-case-slot="video-01"`.
3. Replace that slot's `.case-empty` block with an `<img>` or `<video>` element.

Example image:

```html
<img src="assets/cases/image-01.jpg" alt="A short description of the prompt and result">
```

Example video:

```html
<video controls playsinline poster="assets/cases/video-01-poster.jpg">
  <source src="assets/cases/video-01.mp4" type="video/mp4">
</video>
```
