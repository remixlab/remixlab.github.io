---
layout: post
title: "experiments"
date: 2013-11-23 12:16:17 -0500
comments: true
categories: 
published: false
---

#Code

``` ruby Discover if a number is prime 
http://www.noulakaz.net/weblog/2007/03/18/a-regular-expression-to-check-for-
prime-numbers/ Source Article
class Fixnum
  def prime?
    ('1' * self) !~ /^1?$|^(11+?)\1+$/
  end
end
```

# Latex Formula

$$
\begin{align}
\mbox{Union: } & A\cup B = \{x\mid x\in A \mbox{ or } x\in B\} \\
\mbox{Concatenation: } & A\circ B  = \{xy\mid x\in A \mbox{ and } y\in B\} \\
\mbox{Star: } & A^\star  = \{x_1x_2\ldots x_k \mid  k\geq 0 \mbox{ and each } 
x_i\in A\} \\
\end{align}
$$