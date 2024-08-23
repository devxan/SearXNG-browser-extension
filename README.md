# SearXanNG browser extension
[<img src="./firefox-add-ons.png" title="Firefox Add-ons" width="auto" height="47" />](https://addons.mozilla.org/en-US/firefox/addon/searxanng) <p><a href=""><img src="https://img.shields.io/amo/users/searxanng?style=flat-square" alt="Firefox Addons user count badge" /></a></p>

## SearXNG

**SearXNG** is a free Internet metasearch engine that aggregates results from various search services and databases. Users are not tracked or profiled.

[**SearXNG**](https://github.com/searxng/searxng) is a fork of [**SearX**](https://github.com/searx/searx).

[**Original SearXNG repository on GitHub**](https://github.com/searxng/searxng).

[**SearXNG instances**](https://searx.space/) - you can use other instances of the SearXNG search engine (for this you will need to fork the repository and replace the link for the search query in `manifest.json`).

## Contributing

Install [web-ext](https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/) and run
```
web-ext build 
```
for a version to upload to [Firefox Addons](https://addons.mozilla.org/developers/addons).

## Extension setup + workaround

If you don't want to want use **SearXanNG** as the default search engine:

1. Add the addon on your browser
2. Agree to the browser prompt **"Add this extension?"**
3. Disagree when the browser prompts **"Do you want change your main search engine?"**
4. Use the keyword `@seax` to use **SearXanNG**

## Contributors

[**Erghel**](https://github.com/Erghel) - Main contributor.

[**Rodion Borisov**](https://github.com/vintprox) - Found `"suggestion_url"` and etc.  

[**Ivan Muzyka**](https://github.com/SeryiBaran) - Found icons, etc.

[**Xan**](https://github.com/devxan) - Setup for own instance.
