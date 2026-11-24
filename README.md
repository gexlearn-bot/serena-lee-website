# Serena Lee Photography

One-page personal site for Serena Lee, a wedding and portrait photographer. Plain HTML and CSS, no build step.

## Structure

- `index.html` is the whole page (styles are inline in the `<style>` block).
- `images/` holds the portfolio photos.
- `vercel.json` sets clean URLs and basic headers for Vercel.

## Preview locally

Open `index.html` in a browser, or run `npx serve .` from this folder.

## Deploy on Vercel

1. In Vercel, choose **Add New > Project** and import this repository.
2. Leave the framework preset as **Other**. Leave the build command and output directory empty. Vercel serves the repository root as a static site.
3. Select **Deploy**. Every push to `main` redeploys the site.

## Adding photos

Put each image in `images/`, then replace a `<div class="tile">` in `index.html` with:

```html
<img src="images/your-photo.jpg" alt="Describe the photo">
```

Images show at a 4:5 crop, so portrait-orientation photos work best.

## Placeholders to update

- The email address `hello@serenaleephoto.com` appears in the contact section.
- The about copy is a draft for Serena to rewrite.
