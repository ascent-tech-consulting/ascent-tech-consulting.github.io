# Ascent Technology Consulting

Company homepage.

A simple website 

## Getting Started

Classic jekyll stuff:

```
$ bundle install
$ bundle exec jekyll serve
```

## Features

- Post Support (Blog)
- Pagination and Dynamic Categories
- RSS Feed
- SEO
- Basic Mobile Support
- Syntax Highlighting (prism.js)

## JavaScript Requirements

### Syntax Highlighting

Syntax highlighting from `prism.js` can be customized and switched to a CDN provider if preferred by following 
[these](https://prismjs.com/index.html#basic-usage-cdn) instructions

### Analytics

Support for [Plausible Analytics](https://github.com/plausible) is provided by enabling it within `_config.yml`.

Example configuration: 

``` 
analytics:
  plausible:
    enabled: true
    site_fqdn: 'lightspeed.tajacks.com'
    script_source: 'https://plausible.io/js/script.js'
```

`enabled` - Boolean - To enable or disable page-view analytics.

`site_fqdn` - String - The FQDN of your website to report back to Plausible.

`script_source` - String - The source of the analytics script. Provided as a variable to accommodate self-hosted instances 
of plausible.

## Acknowledgements

Built using the [LightSpeed](https://github.com/tajacks/lightspeed) Jekyll theme by [tajacks](https://github.com/tajacks).
