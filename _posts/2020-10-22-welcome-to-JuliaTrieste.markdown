---
layout: post
title:  "Welcome to Julia@Trieste!"
date:   2020-10-22 23:51:00 +0200
categories: julia trieste
---
This website and its content are work in progress. Please check in later. 

You will most likely find here announcements of training opportunities, tutorials, shared materials, code snippets, resources, community building efforts, etc.


Jekyll also offers powerful support for code snippets:

{% highlight julia %}
function mandelbrot(a)
    z = 0
    for i=1:50
        z = z^2 + a
    end
    return z
end

for y=1.0:-0.05:-1.0
    for x=-2.0:0.0315:0.5
        abs(mandelbrot(complex(x, y))) < 2 ? print("*") : print(" ")
    end
    println()
end
# Taken from: https://rosettacode.org/wiki/Mandelbrot_set#Julia
{% endhighlight %}

