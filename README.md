# Morrow Coffee — Responsive HTML Email Prototype

A polished, **fictional sample campaign** built to demonstrate HTML email frontend skills. This is **not** the client's design: the real design and brand assets have not been supplied.

## Files

- `index.html` — identical visual HTML with relative image paths, intended for a browser preview / GitHub Pages.
- `email-template.html` — email-ready variant with absolute image URLs pointing to the intended GitHub Pages deployment. The URLs only work once the GitHub Pages repository is live under the exact name below.
- `assets/` — local demonstration imagery cropped from scikit-image's bundled coffee example dataset.

## Deployment (public GitHub Pages)

1. Create a **public** GitHub repository named `responsive-html-email-demo`.
2. Upload all files, including the `assets` folder, to the `main` branch root.
3. In repository Settings → Pages → Build and deployment, select **Deploy from a branch**, `main`, `/(root)`, then Save.
4. Wait for the site to publish, then open: `https://utpalsonowal7.github.io/responsive-html-email-demo/`.
5. Check `email-template.html` and ensure the three image URLs load after deployment. For a different repository name, replace the absolute image base URLs.

## Email development notes

The email layout uses presentation tables, inline CSS for major styles, a responsive media query for narrow screens, descriptive image alt text, an email preheader, and an Outlook VML CTA fallback. **Do not claim this is verified in Gmail/Outlook** until real inbox tests are completed. GitHub Pages preview is browser rendering, not inbox testing.

The brand, discount, links and imagery are fictional demonstration content. Replace with final client-provided assets, destinations, and unsubscribe service before shipping.

### Outlook .oft deliverable

Classic Outlook for Windows: compose a new email using the HTML design, verify image links and rendering, then File → Save As → Outlook Template (`*.oft`). Reopen the `.oft` and send tests. The `.oft` file is **not included** in this prototype; it requires classic Outlook to create and validate.

### Testing checklist

- [ ] Desktop browser at ~600px content width
- [ ] Mobile browser at 375px and 390px
- [ ] Gmail web and Gmail mobile real message
- [ ] Classic Outlook Windows real message
- [ ] Outlook web/new Outlook real message
- [ ] CTA, images, social links, unsubscribe placeholders replaced and checked
- [ ] Outlook `.oft` created and manually verified

## License / attribution

Sample photograph is drawn from the `skimage.data.coffee()` sample distributed by scikit-image, for demonstration. Use client-owned or licensed imagery in production.