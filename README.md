Facebook Embedded Posts Octopress Plugin
========================================

This is a plugin for Octopress that allows you to use the [Facebook Embedded Posts feature](https://developers.facebook.com/docs/plugins/embedded-posts/) just using a simple Liquid tag.

Facebook doesn't let you modify the size of the embedded post at this time, but if that changes, I'll update the plugin.

## Installation:
Download the `facebook_embedded_post.rb` file into Octopress's `plugins/` directory within your site.

## Syntax
```ruby
{% facebook_embedded_post url %}
```

## Examples
```ruby
{% facebook_embedded_post https://www.facebook.com/FacebookDevelopers/posts/10151471074398553 %}
```

### Contributors
* [zclancy](https://github.com/zclancy)
