# RSpec HTML Matcher
Provides a very simple `match_html` [RSpec](http://rspec.info) matcher with a pretty decent error message when it doesn't match.

## Installation
Copy-and-paste `match_html.rb` into your project and require it in your `spec_helper`. See the [RSpec docs](http://rspec.info) for details.

If you're using [rspec-rails](https://github.com/rspec/rspec-rails), you can probably stick it in `spec/support` and it will just work.

## Usage
```{ruby}
expect(something).to match_html <<-HTML
  <div class="foo">
    <span>Hi</span>
  </div>
HTML
```
## License
[MIT](https://github.com/eahanson/rspec-html-matcher/blob/master/LICENSE)
