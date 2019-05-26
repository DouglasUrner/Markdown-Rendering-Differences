---
---

# Markdown Rendering Differences

The code below renders "correctly" (does what I want/expect) in a GitHub repository, but breaks when viewed through GitHub Pages. [This link goes to the GitHub Pages site.][ghp] Try the example on both sites to see what happens.

```html
<details>
  <summary>
    Summary Body
  </summary>
  
## The Details
* Thing 1
* Thing 2
  
</details>
```

<details>
  <summary>
    <strong>Live Example: Different rendering of details tag with GFM & Kramdown</strong>
  </summary>
  
## The Details
* Thing 1
* Thing 2
  
</details>

[ghp]: <https://douglasurner.github.io/Markdown-Rendering-Differences/README.html>
