# rspec-html-matcher
Provides a "match_html" Rspec matcher

## Installation
Copy-and-paste into your project :)

For Rails, stick it in `spec/support`

## Usage
```
expect(something).to match_html <<-HTML
  <div class="foo">
    <span>Hi</span>
  </div>
HTML
```
