---
title: Work with Dynamic Data in D3
---
## Work with Dynamic Data in D3

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/data-visualization/data-visualization-with-d3/work-with-dynamic-data-in-d3/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

<a href="https://medium.com/@EleftheriaBatsou/free-code-camp-data-visualization-3d0bccae171f">Click here for the full guide.</a>
selection.text((d) => d);

```javascript
.text((d) => (d + “ USD”))
```
"If a value is specified, sets the text content to the specified value on all selected elements, replacing any existing child elements. If the value is a constant, then all elements are given the same text content; otherwise, if the value is a function, it is evaluated for each selected element, in order, being passed the current datum (d), the current index (i), and the current group (nodes), with this as the current DOM element (nodes[i]). The function’s return value is then used to set each element’s text content. A null value will clear the content. If a value is not specified, returns the text content for the first (non-null) element in the selection. This is generally useful only if you know the selection contains exactly one element." -<a href="https://github.com/d3/d3-selection">D3 Data Driven Documents</a>

