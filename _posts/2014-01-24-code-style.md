---
layout: default
published: true
---

```python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
```



{% highlight ruby linenos %}
require 'rubygems'

def foo
  puts 'foo'
end

#comment
{% endhighlight %}


```ruby
require 'rubygems'

def foo
  puts 'foo'
end

#comment
```



{% highlight python %}
"""Let go"""
import os
print os.name
def fire():
	for i in range(5)
		print i
	
{% endhighlight %}

{{page.date|date:"%Y-%m-%d"}}