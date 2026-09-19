---
layout: post
title: "Example post"
categories:
author:
meta:
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt. Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit.

Hello $\pi(n)$

$$e^\lambda=\sum_{k=0}^\infty\frac{\lambda^k}{k!}$$

## Subheading

Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

> This quote will *change* your life. It will reveal the <i>secrets</i> of the universe, and all the wonders of humanity. Don't <em>misuse</em> it.

```html
<html>
  <head>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
```

- [ ] Milk
- [x] Cookies
  - [x] Classic Choco-chip
  - [x] Sourdough Choco-chip
- [ ] Chee-ee-eeee-zzze!!!!

- First item, yo
- Second item, dawg
- Third item, what what?!
- Fourth item, fo sheezy my neezy
- Fifth item, nested!
  - So la ti do
  - Ba-da-bing!
  - Ba-da-boom!

1. First item, yo
2. Second item, dawg
3. Third item, what what?!
4. Fourth item, fo sheezy my neezy
5. Fifth item, nested!
  - So la ti do
  - Ba-da-bing!
  - Ba-da-boom!

### Tables

Title 1               | Title 2               | Title 3               | Title 4
--------------------- | --------------------- | --------------------- | ---------------------
lorem                 | lorem ipsum           | lorem ipsum dolor     | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit


Title 1 | Title 2 | Title 3 | Title 4
--- | --- | --- | ---
lorem | lorem ipsum | lorem ipsum dolor | lorem ipsum dolor sit
lorem ipsum dolor sit amet | lorem ipsum dolor sit amet consectetur | lorem ipsum dolor sit amet | lorem ipsum dolor sit
lorem ipsum dolor | lorem ipsum | lorem | lorem ipsum
lorem ipsum dolor | lorem ipsum dolor sit | lorem ipsum dolor sit amet | lorem ipsum dolor sit amet consectetur

### Code blocks

An article with various blocks of highlighted code snippets.

```ruby
=begin
  Dummy class nested inside a dummy module
  Private API
=end
```
```diff
- This line is redacted
- This line has been deleted
+ This line is visible
+ This line has been inserted
This line has not been changed
```
```sass
@import "base"

.card
  display: inline-block
  margin: 0
  padding: 0

  &:hover
    color: #ab45ef;
```
```ruby
21 + 54 = 0
foo ||= bar
foo / bar

24
45.75
0x2C716
\x0A
01010

/ya?ml/
"yaml"
```
```ruby
include Enumerable

module Foo
  class Bar
    LIPSUM = "lorem ipsum dolor sit"

    attr_reader :layout

    def initialize
      @layout = Layout.new
    end

    # instance method
    def profile
      measure_time do
        compile layout
        layout.render_with Bar::LIPSUM
      end
    rescue ArgumentError
      false
    end
  end
end

# Execute code
Foo::Bar.new.profile
```

{% raw %}
```liquid
{% assign foo = page.foo | bar: 'baz' %}
{{ foo }}
```
{% endraw %}

```yaml
author:
  admin: true
  name: John Doe
  email: johndoe@example.com
  id: 75636474
```

{% highlight html %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>Hello World</title>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
{% endhighlight %}

{% highlight html mark_lines="1 4 7" %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>Hello World</title>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
{% endhighlight %}

{% highlight html linenos %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>Hello World</title>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
{% endhighlight %}

{% highlight html linenos mark_lines="1 4 7" %}
<html>
  <head>
    <meta charset="utf-8" />
    <title>Hello World</title>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
{% endhighlight %}