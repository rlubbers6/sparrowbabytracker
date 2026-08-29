# Sparrow: Baby Tracker — public pages

This repository exists only to host the public pages for **Sparrow: Baby
Tracker**, at the URLs referenced by the App Store listing and by the app
itself:

- Privacy policy — <https://rlubbers6.github.io/sparrowbabytracker/>
- Support — <https://rlubbers6.github.io/sparrowbabytracker/support.html>

## Do not edit the HTML here

`index.html` and `support.html` are **generated**. The sources of truth are
`docs/privacy-policy.md` and `docs/support.md` in the app's own (private)
repository, and both pages are produced from them by one script:

```
node scripts/build-pages.mjs <path-to-this-repo>
```

Editing the HTML directly means the published documents and the ones that ship
with the app quietly disagree — which, for a policy a user relies on to
understand what happens to their child's medical records, is the one outcome
worth engineering against. Both pages share a single renderer for the same
reason: a support page that slowly stops looking like the privacy policy is a
support page nobody believes is official.

The app's source is not published here; it stays private.
