# Brenden Hardy · Portfolio

My personal portfolio site: web projects, apps and 3D modelling. When it's published, it will be live at **https://doggieshrimp.github.io/**

It's a single hand-written HTML page (no frameworks or build step) with these sections:

- **Web projects**
  - [Ball Battle](https://github.com/doggieshrimp/Ball-battle): a browser battle simulator with hand-written physics and 9 powers.
  - [CodeBreaker](https://github.com/doggieshrimp/CodeBreaker): create and decode secret messages with 7 ciphers, including real AES-256.
  - [SmoothFinish](https://github.com/doggieshrimp/SmoothFinish): a website for a local ironing business.
- **Apps:** StudyXP, a gamified study app built with Flutter (in development).
- **3D modelling:** services I offer (game assets, character renders, custom commissions) and a gallery of renders.

## Adding 3D renders

Put the image in `images/3d/`, then in `index.html` replace one of the `render placeholder` blocks with:

```html
<div class="render"><img src="images/3d/your-render.jpg" alt="Short description of the render" loading="lazy"></div>
```

Renders look best at a 16:9 ratio (for example 1600×900).
