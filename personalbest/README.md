# PersonalBest public pages

Pages for the PersonalBest app, served by GitHub Pages from the
`public-pages` repository. Each project keeps its files in its own folder.

```
personalbest/
  index.html            # links to the pages below
  privacy/index.html    # privacy policy (English / 日本語)
  .nojekyll             # serve the files as-is, no Jekyll processing
```

The policy text mirrors `PrivacyPolicyView.swift` in the app; when the
app's policy changes, update this page and its "Last updated" date in the
same release.

## Publishing

GitHub → repository Settings → Pages → Source: "Deploy from a branch",
branch `main`, folder `/ (root)`.

Privacy policy URL: `https://new-wave-software.github.io/public-pages/personalbest/privacy/`
