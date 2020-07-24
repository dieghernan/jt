[![Chulapa live preview][2]][1]

[1]: https://dieghernan.github.io/chulapa/
[2]: https://dieghernan.github.io/chulapa/assets/img/site/banner.png (live preview)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/dieghernan/chulapa) ![GitHub](https://img.shields.io/github/license/dieghernan/chulapa) ![Jekyll](https://img.shields.io/badge/jekyll-3.8.7-blue) ![Bootstrap](https://img.shields.io/badge/bootstrap-4.5.0-blue) ![Fontawesome](https://img.shields.io/badge/fontawesome->5.0.0-blue) ![Algolia](https://img.shields.io/badge/algolia->4.7.0-blue) ![lunr](https://img.shields.io/badge/lunr-2.3.8-blue) ![mathjax](https://img.shields.io/badge/mathjax-2.7.1-blue) ![GHpages](https://img.shields.io/badge/gh--pages-ready-succes) ![google-analytics](https://img.shields.io/badge/google--analytics-ready-succes) ![disqus](https://img.shields.io/badge/disqus-ready-succes) ![social sharing](https://img.shields.io/badge/social--sharing-ready-succes) ![seo](https://img.shields.io/badge/seo-ready-succes) ![video](https://img.shields.io/badge/video--support-ok-succes)

# [Chulapa](https://dieghernan.github.io/chulapa/)

### A full flexible Jekyll theme for Github Pages

## Notable features

-  **Bootstrap 4** - Fully responsive
-  **Fontawesome 5** - v4 is supported via shims but would be deprecated at some point
-  **3 different navbar styles**
-  **Atom and RSS 2.0** feed
-  **Internal search** by Algolia, Lunr or Google Custom Search
-  **Comments** by Disqus
-  **Masonry gallery**
-  **Video support** - self-hosted or from core providers: Youtube, Vimeo, DailyMotion...
-  **Structured data** for better SEO
-  **Google Analytics**
-  **Twitter Cards** and **Open Graph** data valid for Facebook, LinkedIn and WhatsApp
-  **14+ preinstalled skins**
-  **Powerful look-and-feel customization**
-  **Archive, cloud tag and index special layouts**

The right choice for blogs, news, portfolios and personal sites. Want to know more? [Go to Docs](https://dieghernan.github.io/chulapa/docs/01-install).

## Installation
### A. Remote theme method

By using `jekyll-remote-theme` your repo would have remote access to the content of these folders:

- `chulapa/assets`
- `chulapa/_layouts`
- `chulapa/_includes`
- `chulapa/_sass`

This method allows you to get updates easily

#### Fresh start

Create a Github account, go to [chulapa-101 repo](https://github.com/dieghernan/chulapa-101), fork it and quickstart your site!

#### Migrate

You can migrate an existing page adding this line to your `_config.yml` and make sure to remove any previous theme or remote theme parameter:
  
```yaml
remote_theme: dieghernan/chulapa@[releasetag]

... more config options
```
    
Replace `[releasetag]` with the desired release tag, or just use `dieghernan/chulapa` if you want to use the `master` branch version of the theme (on active development).


### B. Fork the base repository

You can fork [the base repo](https://github.com/dieghernan/chulapa/generate) and modify it. However, the site would be frozen at the moment of forking and it would make harder for you to get potential new features and upgrades.

The minimal files and folders you need are:
 
- `chulapa/assets`
- `chulapa/_layouts`
- `chulapa/_includes`
- `chulapa/_sass`
- `Gemfile`
- `_config.yml`

Sample `_config` file [here](https://github.com/dieghernan/chulapa/blob/master/_config.yml).

## Configuration and Layouts

You have available an extensive documentation [here](https://dieghernan.github.io/chulapa/docs/01-install)

## License

[The MIT License](https://dieghernan.github.io/chulapa/license)
