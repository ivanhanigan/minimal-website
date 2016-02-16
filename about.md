---
layout: default
---

### About

- this is the thing

{% highlight r %}  
data("iris")
plot(iris$Sepal.Length ~ iris$Sepal.Width)
dat <- rnorm(1000, 1, 2)
{% endhighlight %}

Is that good?

{% highlight r %}
png("hist.png")
hist(dat)
dev.off()
{% endhighlight %}

![hist.png](hist.png)



