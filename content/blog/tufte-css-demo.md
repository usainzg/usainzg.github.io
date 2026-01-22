---
title: "Tufte CSS: A Beautiful Typography System"
date: 2026-01-22
tags: ["design", "typography", "web"]
author: ["Unai Sainz de la Maza"]
description: "An exploration of Edward Tufte's design principles applied to web typography."
summary: "An exploration of Edward Tufte's design principles applied to web typography, featuring sidenotes, margin notes, and beautiful typography."
---

# Introduction

<span class="newthought">Edward Tufte</span> is a statistician and artist, and Professor Emeritus of Political Science, Statistics, and Computer Science at Yale University. He wrote, designed, and self-published four classic books on data visualization.<label for="sn-beautiful-evidence" class="margin-toggle sidenote-number"></label><input type="checkbox" id="sn-beautiful-evidence" class="margin-toggle"/><span class="sidenote">The books include <em>The Visual Display of Quantitative Information</em>, <em>Envisioning Information</em>, <em>Visual Explanations</em>, and <em>Beautiful Evidence</em>.</span>

Tufte's style is known for its simplicity, extensive use of sidenotes, tight integration of graphics with text, and carefully chosen typography. This post demonstrates how Tufte CSS brings these principles to the web.

## Typography and Text

One of the key design decisions in Tufte CSS is the use of <a href="https://github.com/edwardtufte/et-book">ET Book</a>, a typeface designed to mimic the look of Monotype Bembo, the font used in Tufte's printed books. ET Book is now open source and available for use on the web.<label for="mn-et-book" class="margin-toggle">&#8853;</label><input type="checkbox" id="mn-et-book" class="margin-toggle"/><span class="marginnote">This is a margin note. Unlike sidenotes, margin notes don't have numbers.</span>

The body text is set at a comfortable reading width, with ample margins for sidenotes and margin notes. Links are underlined but match the body text color, avoiding the garish blue typically seen on the web.

## Sidenotes and Margin Notes

Sidenotes are one of the most distinctive features of Tufte's design. They serve the same purpose as footnotes, but they're displayed in the margin rather than at the bottom of the page. This keeps the reader's eye on the page and maintains the flow of reading.<label for="sn-sidenotes-advantage" class="margin-toggle sidenote-number"></label><input type="checkbox" id="sn-sidenotes-advantage" class="margin-toggle"/><span class="sidenote">On small screens, sidenotes appear inline when the reader clicks on the reference number, providing a graceful degradation of the design.</span>

### Code Examples

Here's a simple code example showing how to create a sidenote in HTML:

```html
<label for="sn-demo" class="margin-toggle sidenote-number"></label>
<input type="checkbox" id="sn-demo" class="margin-toggle"/>
<span class="sidenote">This is a sidenote.</span>
```

And here's a Python example with syntax highlighting:

```python
def fibonacci(n):
    """Calculate the nth Fibonacci number."""
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

# Example usage
result = fibonacci(10)
print(f"The 10th Fibonacci number is {result}")
```

## Mathematical Expressions

Tufte was particularly concerned with the display of quantitative information. Mathematical expressions should integrate seamlessly with the text. For instance, the quadratic formula is given by:

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

Inline math also works: the fundamental theorem of calculus states that $\int_a^b f'(x)\,dx = f(b) - f(a)$.

## Epigraphs

<div class="epigraph">
<blockquote>
<p>The English language becomes ugly and inaccurate because our thoughts are foolish, but the slovenliness of our language makes it easier for us to have foolish thoughts.</p>
<footer>George Orwell, "Politics and the English Language"</footer>
</blockquote>
</div>

Epigraphs can be used to introduce sections with relevant quotations. They are styled in italics and attributed to their source.

## Lists and Organization

Tufte CSS supports all standard HTML list types:

1. **Ordered lists** use numbers
2. Each item is clearly separated
3. The spacing is comfortable for reading

Unordered lists work equally well:

- Bullet points are subtle
- They don't distract from the content
- The focus remains on the text

## Tables

Tables in Tufte CSS are simple and clean, following the booktabs style:

| Year | Temperature Anomaly (°C) | Sea Level Rise (mm) |
|------|-------------------------|---------------------|
| 2000 | +0.40                   | 0                   |
| 2010 | +0.72                   | 32                  |
| 2020 | +1.02                   | 68                  |

The emphasis is on data, not decoration. Lines are used sparingly, and the typography does the work of organizing information.

## Conclusion

Tufte CSS demonstrates that web typography can be both beautiful and functional. By following Tufte's principles of design clarity and reader respect, we can create web pages that are a joy to read.<label for="sn-conclusion" class="margin-toggle sidenote-number"></label><input type="checkbox" id="sn-conclusion" class="margin-toggle"/><span class="sidenote">For more information, see the <a href="https://edwardtufte.github.io/tufte-css/">Tufte CSS homepage</a> and the <a href="https://www.edwardtufte.com/tufte/">works of Edward Tufte</a>.</span>

The key is to prioritize content over decoration, use whitespace effectively, and integrate supplementary information (like sidenotes) in a way that enhances rather than interrupts the reading experience.
