---
title: "An example of a single-threaded approach to a task that unfolds over time"
toc_sticky: true 
source1: "drive_square_sample_1/drive_square_sample_1.py" 
---

## Basic Example of a Node that Executes a Task over a Sequence of Steps

This code provides a specific way to architect code that executes a task consisting of a sequence of steps (in this case driving a square).  This can be improved in many ways, so let me know what you think could be done to make it cleaner.

<a href="{{ page.source1 }}">Source: drive_square_sample_1.py</a>

{% highlight python %}
{% include_relative {{ page.source1 }} %}
{% endhighlight %}
