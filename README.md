# SearXNG-browser-extension (Unofficial fork for my own host)
[<img src="./firefox-add-ons.png" title="Firefox Add-ons" width="auto" height="47" />](https://addons.mozilla.org/en-US/firefox/addon/searxng-search) <p><a href=""><img src="https://img.shields.io/amo/users/searxng-search?style=flat-square" alt="Badge" /></a></p>

# SearXNG

**SearXNG** is a free Internet metasearch engine that aggregates results from various search services and databases. Users are not tracked or profiled.

[**SearXNG**](https://github.com/searxng/searxng) is a fork of [**SearX**](https://github.com/searx/searx).

[**Original SearXNG repository on GitHub**](https://github.com/searxng/searxng).

[**SearXNG instances**](https://searx.space/) - you can use other instances of the SearXNG search engine (for this you will need to fork the repository and replace the link for the search query in `manifest.json`).

# How does extension work?
Extension use `manifest.json` settings which change your main search engine.

Example:

(**Default settings**)
```json
{
  "chrome_settings_overrides": {
    "search_provider": {
      "search_url": "https://example.com/search?q={searchTerms}"
    }
  }
}
```

(**With addon**)
```json
{
  "chrome_settings_overrides": {
    "search_provider": {
      "search_url": "https://host.xan.lol/searxng/search?q={searchTerms}"
    }
  }
}
```

It means that your browser starts to use second link when you make search request.

# Extension setup + workaround
If you want use **SearXNG** as support to main search engine do this:
1. Add the addon on your browser
2. Agree to the browser prompt **"Add this extension?"**
3. Disagree when the browser prompts **"Do you want change your main search engine?"**
4. Use keywords like `@searxng, @searx, @sx` when you want to use **SearXNG** when you make request

# Contributors
[**Erghel**](https://github.com/Erghel) - Main contributor.

[**Rodion Borisov**](https://github.com/vintprox) - Found `"suggestion_url"` and etc.  

[**Ivan Muzyka**](https://github.com/SeryiBaran) - Found icons, etc.

[**Xan**](https://github.com/devxan) - Setup for own instance.
