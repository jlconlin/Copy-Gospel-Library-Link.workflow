# GL-Link-Substitution
An OSX Service to copy a URL from [www.lds.org](http://www.lds.org) for use in gospel library

This service will take selected text in a browser like

[https://www.lds.org/manual/old-testament-seminary-teacher-manual/introduction-to-the-book-of-isaiah/lesson-127-isaiah-51-52?lang=eng] (https://www.lds.org/manual/old-testament-seminary-teacher-manual/introduction-to-the-book-of-isaiah/lesson-127-isaiah-51-52?lang=eng)

and replaces:

 - `https` with `gospellibrary`, and 
 - `www.lds.org` with `content`.  

This facilitates copying links and pasting them into another document with links to the Gospel Library app on an iOS device.

## Usage
This service takes whatever is on the clipboard and attempts to do the substitutions as explained above. Using this service is greatly enhanced when you have created a system-wide keyboard shortcut. With a shortcut defined, simply right-click a link on [www.lds.org](http://www.lds.org), choose `Copy Link` which copies the URL to the clipboard. Now simply execute the keyboard shortcut and the modified URL is copied to the clipboard.

## Installation
```
cd ~/Library/Services
git clone git@github.com:jlconlin/GL-Link-Substitution.git 
```

### Creating a system-wide shortcut
Open System Preferences. Navigate to Keyboard->Shortcuts and select Services on the left side. Find `Copy-Gospel-Library-Link` under the `Text` item on the right. Choose a keyboard shortcut and push those keys to create the shortcut. I chose command-G (⌘G) for mine.

