# GL-Link-Substitution
An OSX Service to copy a URL from lds.org for use in gospel library

This will take selected text in a browser like

```
https://www.lds.org/manual/old-testament-seminary-teacher-manual/introduction-to-the-book-of-isaiah/lesson-127-isaiah-51-52?lang=eng
```

and replace the `https` with `gospellibrary` and `www.lds.org` with `content`.  This facilitates copying links ans pasting them into another document with links to the Gospel Library app on an iOS device.

## Installation
```
cd ~/Library/Services
git clone git@github.com:jlconlin/GL-Link-Substitution.git "Copy Gospel Library Link.workflow"
```

