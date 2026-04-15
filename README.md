# Storease Legal Pages

These files are prepared to be copied into the root of the external legal-site repository:

- [storease.io](https://github.com/DavisKiprotich/storease.io)

Expected structure in that repo root:

- `index.html`
- `privacy/index.html`
- `terms/index.html`
- `.nojekyll`
- `README.md`

Expected GitHub Pages URLs after publish:

- `https://daviskiprotich.github.io/storease.io/`
- `https://daviskiprotich.github.io/storease.io/privacy/`
- `https://daviskiprotich.github.io/storease.io/terms/`

The app opens the legal pages with a language query parameter, for example:

- `...?lang=en`
- `...?lang=fr`
- `...?lang=es`
- `...?lang=pt`
- `...?lang=ar`
- `...?lang=zh`

Publishing steps for the external repo:

1. Copy the contents of this `docs/legal` folder into the root of `storease.io`.
2. Commit and push to the `main` branch of `storease.io`.
3. In GitHub Pages settings for `storease.io`, publish from the repository root.
4. Wait for GitHub Pages to build the site.

If the final public URL changes, update:

- [legalLinks.ts](/E:/Code/Storease/src/config/legalLinks.ts)
