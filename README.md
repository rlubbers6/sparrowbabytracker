# Sparrow: Baby Tracker — privacy policy

This repository exists only to host the privacy policy for **Sparrow: Baby
Tracker** as a public web page, at the URL referenced by the App Store listing:

<https://rlubbers6.github.io/sparrowbabytracker/>

## Do not edit `index.html` here

It is **generated**. The source of truth is `docs/privacy-policy.md` in the
app's own (private) repository, and the page is produced from it by
`scripts/build-privacy-page.mjs`:

```
node scripts/build-privacy-page.mjs <path-to-this-repo>
```

Editing the HTML directly means the published policy and the one that ships
with the app quietly disagree — which, for the document a user relies on to
understand what happens to their child's medical records, is the one outcome
worth engineering against.

The app's source is not published here; it stays private.
