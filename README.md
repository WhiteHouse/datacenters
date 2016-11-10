##

The [Office of Management and Budget (OMB)](https://www.whitehouse.gov/omb/) has issued the [Data Center Optimization Initiative (DCOI)](https://www.whitehouse.gov/sites/default/files/omb/memoranda/2016/m_16_19_1.pdf) to advance the consolidation and optimization of the Federal Government’s inventory of data centers.  The DCOI supersedes the Federal Data Center Consolidation Initiative (FDCCI) and addresses requirements in the Federal Information Technology Acquisition Reform Act (FITARA).

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

### Privacy

All comments, messages, pull requests, and other submissions received through official White House pages including this GitHub page may be subject to archiving requirements. See the https://www.whitehouse.gov/privacy for more information.

### Developing on the site locally

This site uses [Jekyll](http://jekyllrb.com), [Sass](http://sass-lang.com), [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io), and requires **Ruby 2.x**.

Install dependencies with Bundler:

```
bundle install
```

For local development, uncomment the following line in `_config.yml`:

```
baseurl: /datacenters/
```

And run the site with Jekyll:

```
bundle exec jekyll serve --watch
```

If all goes well, visit the site at `http://localhost:4000`.
