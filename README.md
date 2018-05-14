# Theme Cayman

This is a [Jekyll][1] theme based on [@jasonlong][2]'s [Cayman theme][4] from [GitHub Pages][3].

# How to use it?

Download the theme @ https://github.com/java-tools/theme-cayman/archive/master.zip

Unzip it and use it as a regular jekyll folder.

```
$ unzip theme-cayman-master.zip
```

Get inside the newly extracted folder
```
$ cd theme-cayman-master
```

Get the required gems
```
$ bundle install
```

Use it!

```
$ jekyll serve
```

For more details read about [Jekyll][1] on its web page.

# Setup

Some important configuration can be done in the file `_config.yml`. Please, check the Setup section in that file.


## baseurl

`baseurl` parameter is required in the case the site doesn't sit on the root of the domain. For example: https://java-tools.github.io/theme-cayman

In the case above the baseurl should be set to "/theme-cayman".

In the case the site sits in the root, you can leave `baseurl` as empty "".

# Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/java-tools/theme-cayman.

# Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

# License

This work is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

[1]: https://jekyllrb.com/
[2]: https://github.com/jasonlong
[3]: https://pages.github.com/
[4]: https://github.com/jasonlong/cayman-theme
