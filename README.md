# uBlogger Theme | Hugo

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/upagge/uBlogger?style=flat-square)](https://github.com/upagge/uBlogger/releases)
[![Hugo](https://img.shields.io/badge/Hugo-%5E0.62.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/)
[![License](https://img.shields.io/github/license/upagge/uBlogger?style=flat-square)](https://github.com/upagge/uBlogger/blob/master/LICENSE)
> **uBlogger** is a **clean**, **elegant** but **advanced** blog theme for [Hugo](https://gohugo.io/).

## :warning: Information for those who move with LoveIt theme

> Skip to the next section if you do not know about LoveIt

Hello! Too bad, but the developer of LoveIt hasn't responded to my messages for many weeks, and his last activity at GitHub was in May.

I decided that I would develop the project further, but under a different brand - uBlogger. As the author of LoveIt created his project based on LeaveIt Theme and KeepIt Theme.

Now the **official language of support is English**, I have removed the version of the documentation in French and Chinese, as I do not know them, I hope you will forgive me :).

Here is a brief list of changes, more details can be found in the documentation.

The main emphasis is on the convenience of reading content, because we have a blog. So the big changes have been made in the form of posts.

## What have I managed to change

> While there is no demo site, you can see how the template looks on [my blog](https://blog.upagge.ru).

* Now the article page can have three views, and in combination with the positioning of content you have the flexibility to change the format of displaying the article.
* I took the changes in their PRs that fixed the bugs: [#558](https://github.com/dillonzq/LoveIt/pull/558/files), [#544](https://github.com/dillonzq/LoveIt/pull/544/files), [#522](https://github.com/dillonzq/LoveIt/pull/522), [#521](https://github.com/dillonzq/LoveIt/pull/521), [#519](https://github.com/dillonzq/LoveIt/pull/519), [#461](https://github.com/dillonzq/LoveIt/pull/461/files), [#433](https://github.com/dillonzq/LoveIt/pull/433/files), [#425](https://github.com/dillonzq/LoveIt/pull/425)
* Added breadcrumbs support for OpenGraph
* Support for [Remark 42](https://github.com/umputun/remark42/) comments. Ooo is a great project and I strongly recommend using this commenting system for your site. Soon I will write an article why it is the best commenting system and how to set it up. Personally, I use it in [my blog](https://blog.upagge.ru).
* Added support for [yandex metrics](http://metrika.yandex.com/)
* I also made a lot of small improvements, and this is just the beginning :smile:

If you have ideas or suggestions, or if you find bugs, please report them to the [issue](https://github.com/uPagge/uBlogger/issues).

**If you liked the topic, I would be glad if you gave a :star2: star to this project. Well, either throw me a coffee via [PayPal](https://paypal.me/upagge)**

### Change the markdown design

1. The `em` tag is no longer slanted, it is now a marker selection.

2. The quote is no longer a quote, but a focus on important aspects.

## Info about theme

It is based on the original [LoveIt Theme](https://github.com/dillonzq/LoveIt).

Since the three themes have a similar look, if you have questions about their differences,
read [Why choose uBlogger](#why-choose-ublogger) so that you can choose the one that works best for you.

![Hugo Theme uBlogger](https://github.com/upagge/uBlogger/raw/master/images/Apple-Devices-Preview.png)

## [Demo Site](https://blog.upagge.ru/)

To see this theme in action, here is a live [demo site](https://blog.upagge.ru/) which is rendered with **uBlogger** theme.

## Why choose uBlogger

Compared to the original LeaveIt theme and the KeepIt theme, the uBlogger theme has the following modifications.

* Custom **Header**
* Custom **CSS Style**
* A new **home page**, compatible with the latest version of Hugo
* A lot of **style detail adjustments,** including color, font size, margins, code preview style
* More readable **dark mode**
* Some beautiful **CSS animations**
* Easy-to-use and self-expanding **table of contents**
* More **social links**, **share sites** and **comment system**
* **Search** supported by [Lunr.js](https://lunrjs.com/) or [algolia](https://www.algolia.com/)
* **Copy code** to clipboard with one click
* Extended Markdown syntax for **[Font Awesome](https://fontawesome.com/) icons**
* Extended Markdown syntax for **ruby annotation**
* Extended Markdown syntax for **fraction**
* **Mathematical formula** supported by [KaTeX](https://katex.org/)
* **Diagram syntax** shortcode supported by [mermaid](https://github.com/knsv/mermaid)
* **Interactive data visualization** shortcode supported by [ECharts](https://echarts.apache.org/)
* **Mapbox** shortcode supported by [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js)
* Embedded **music player** supported by [APlayer](https://github.com/MoePlayer/APlayer) and [MetingJS](https://github.com/metowolf/MetingJS)
* **Bilibili** player supported
* Kinds of **admonitions** shortcode supported
* Custom style shortcodes supported
* **CDN** for all third-party libraries supported
* ...

In short,
if you prefer the design language and freedom of the uBlogger theme,
if you want to use the extended Font Awesome icons conveniently,
if you want to embed mathematical formulas, flowcharts, music or Bilibili videos in your posts,
the uBlogger theme may be more suitable for you.

I hope you will uBlogger ❤️!

## Features

### Performance and SEO

* Optimized for **performance**: 99/100 on mobile and 100/100 on desktop in [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights)
* Optimized SEO performance with a correct **SEO SCHEMA** based on JSON-LD
* **[Google Analytics](https://analytics.google.com/analytics)** supported
* **[Fathom Analytics](https://usefathom.com/)** supported
* Search engine **verification** supported (Google, Bind, Yandex and Baidu)
* **CDN** for third-party libraries supported
* Automatically converted images with **Lazy Load** by [lazysizes](https://github.com/aFarkas/lazysizes)

### Appearance and Layout

* **Responsive** layout
* **Light/Dark** mode
* Globally consistent **design language**
* **Pagination** supported
* Easy-to-use and self-expanding **table of contents**
* **Multilanguage** supported and i18n ready
* Beautiful **CSS animation**

### Social and Comment Systems

* **Gravatar** supported by [Gravatar](https://gravatar.com)
* Local **Avatar** supported
* Up to **64** social links supported
* Up to **28** share sites supported
* **Disqus** comment system supported by [Disqus](https://disqus.com)
* **Gitalk** comment system supported by [Gitalk](https://github.com/gitalk/gitalk)
* **Valine** comment system supported by [Valine](https://valine.js.org/)
* **Facebook comments** system supported by [Facebook](https://developers.facebook.com/docs/plugins/comments/)
* **Telegram comments** system supported by [Telegram Comments](https://comments.app/)
* **Commento** comment system supported by [Commento](https://commento.io/)
* **Utterances** comment system supported by [Utterances](https://utteranc.es/)

### Extended Features

* **Search** supported by [Lunr.js](https://lunrjs.com/) or [algolia](https://www.algolia.com/)
* **Twemoji** supported
* Automatically **highlighting** code
* **Copy code** to clipboard with one click
* **Images gallery** supported by [lightgallery.js](https://github.com/sachinchoolur/lightgallery.js)
* Extended Markdown syntax for **[Font Awesome](https://fontawesome.com/) icons**
* Extended Markdown syntax for **ruby annotation**
* Extended Markdown syntax for **fraction**
* **Mathematical formula** supported by [KaTeX](https://katex.org/)
* **Diagrams** shortcode supported by [mermaid](https://github.com/knsv/mermaid)
* **Interactive data visualization** shortcode supported by [ECharts](https://echarts.apache.org/)
* **Mapbox** shortcode supported by [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js)
* **Music player** shortcode supported by [APlayer](https://github.com/MoePlayer/APlayer) and [MetingJS](https://github.com/metowolf/MetingJS)
* **Bilibili player** shortcode
* Kinds of **admonitions** shortcode
* **Custom style** shortcode
* **Custom script** shortcode
* **Animated typing** supported by [TypeIt](https://typeitjs.com/)
* **Dynamic scroll** supported by [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* **Cookie consent banner** supported by [cookieconsent](https://github.com/osano/cookieconsent)
* ...

## Documentation

Build Documentation Locally:

```bash
hugo server --source=exampleSite
```

## Multilingual and i18n

uBlogger supports the following languages:

* English
* Simplified Chinese
* French
* Polish
* Brazilian Portuguese
* Italian
* Spanish
* German
* Serbian
* Russian
* Romanian
* Vietnamese
* [Contribute with a new language](https://github.com/upagge/uBlogger/pulls)

## Questions, ideas, bugs, pull requests

All feedback is welcome! Head over to the [issue tracker](https://github.com/upagge/uBlogger/issues).

## License

uBlogger is licensed under the **MIT** license. Check the [LICENSE file](https://github.com/upagge/uBlogger/blob/master/LICENSE) for details.

Thanks to the authors of following resources included in the theme:

* [normalize.css](https://github.com/necolas/normalize.css)
* [Font Awesome](https://fontawesome.com/)
* [Simple Icons](https://github.com/simple-icons/simple-icons)
* [Animate.css](https://daneden.github.io/animate.css/)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [autocomplete.js](https://github.com/algolia/autocomplete.js)
* [Lunr.js](https://lunrjs.com/)
* [algoliasearch](https://github.com/algolia/algoliasearch-client-javascript)
* [lazysizes](https://github.com/aFarkas/lazysizes)
* [object-fit-images](https://github.com/fregante/object-fit-images)
* [Twemoji](https://github.com/twitter/twemoji)
* [lightgallery.js](https://github.com/sachinchoolur/lightgallery.js)
* [clipboard.js](https://github.com/zenorocha/clipboard.js)
* [Sharer.js](https://github.com/ellisonleao/sharer.js)
* [TypeIt](https://typeitjs.com/)
* [KaTeX](https://katex.org/)
* [mermaid](https://github.com/knsv/mermaid)
* [ECharts](https://echarts.apache.org/)
* [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js)
* [APlayer](https://github.com/MoePlayer/APlayer)
* [MetingJS](https://github.com/metowolf/MetingJS)
* [Gitalk](https://github.com/gitalk/gitalk)
* [Valine](https://valine.js.org/)
* [cookieconsent](https://github.com/osano/cookieconsent)

## Author

[Dillon](https://dillonzq.com)

## Sponsor

If you enjoy the theme, please consider buying me a coffee ☕️.

* [PaiPal](https://paypal.me/upagge)

Thanks! ❤️
