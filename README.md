# mozillaExtenstion
# borderify

**This add-on injects JavaScript into web pages. The `addons.mozilla.org` domain disallows this operation, so this add-on will not work properly when it's run on pages in the `addons.mozilla.org` domain.**

## What it does

This extension just includes:

* a content script, "borderify.js", that is injected into any pages
under "mozilla.org/" or any of its subdomains

The content script draws a border around the document.body.

## What it shows

* how to inject content scripts declaratively using manifest.json

## Install and test

* Open "about:debugging" in Firefox, click "Load Temporary Add-on" and select any file in your extension's directory. 
The extension will now be installed, and will stay until you restart Firefox.
Alternatively, you can run the extension from the command line using the web-ext tool.

### Test
* Try visiting a page under "mozilla.org", and you should see the red border round the page.
