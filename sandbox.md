---
layout: default
---

This page is for playing with markdown and Github Flavored Markdown (GFM)

# Header 1

## Table

First Header | Second Header
------------ | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell
Content Cell | Content Cell

## Header 2

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua.  Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum 

## Links

* http://nateneff.com - An automatic link

# Source Code

{% highlight ruby %}
def foo
    puts 'foo'
end
{% endhighlight ruby %}

{% highlight scala %}

val boo = 5
{% endhighlight ruby %}

# Misc

## No Intra Emphasis

this_word_should_not_be_emphasized because the underscores are inside the word.

_these_ _words_ should be emphasized

 these words also_ should be emphasized
