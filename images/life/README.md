# Adding photos to "Photos & Life"

1. Upload your image to this `images/life` folder. Use a short filename with no spaces, such as `sfn-2025.jpg`.
2. Open `_pages/photos-life.md` in GitHub and click the pencil icon to edit it.
3. Copy this block inside the `<div class="life-gallery">` section:

```html
<figure class="life-photo">
  <img src="{{ '/images/life/sfn-2025.jpg' | relative_url }}" alt="Yufan presenting a poster at SfN">
  <figcaption>
    <strong>Society for Neuroscience</strong>
    <span>Chicago &middot; 2025</span>
    <p>Presenting our latest work and catching up with friends.</p>
  </figcaption>
</figure>
```

4. Change the filename, description, title, place, year, and caption.
5. Commit the changes. GitHub Pages will update the website automatically.

For best results, use JPG or WebP images under 1 MB. Landscape and portrait photos are both supported. The `alt` text should briefly describe the image for visitors using screen readers.
