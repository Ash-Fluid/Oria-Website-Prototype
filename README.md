# Oria website prototype

Static prototype of a simplified fluidmedical.com: four pages, no build step.

| Page | File |
|---|---|
| Home | `index.html` |
| Oria (product) | `oria.html` |
| Women's health | `womens-health.html` |
| About | `about.html` |

Images are in `assets/`. The two test-card images are also embedded in the HTML.

## Publish with GitHub Pages

1. Create a repository and upload everything in this folder.
2. In the repository, open Settings → Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then save.
4. The site appears at `https://<username>.github.io/<repository>/` after a minute or two.

## Notes

- Light and dark styles: the toggle is in the home page nav and the choice is remembered on the other pages.
- This is a prototype. The waitlist form is not connected to anything.
- Pages carry a `noindex` tag so search engines do not list them.
- Links to pages that are not prototyped (Security, Contact, Demo, Perspectives) go to the live fluidmedical.com.
- The Oria page embeds the test flow from `https://ash-fluid.github.io/Oria-Testing-Process/`.
- Fonts load from Google Fonts.
