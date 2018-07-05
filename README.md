## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/tylerwatkins101/cs498-visualization-project/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<!DOCTYPE html>
<script src="http://d3js.org/d3.v3.min.js"></script>
<style> .chart rect { fill: steelblue } </style>

<html><body>
<p>Here are the magic numbers from Lost: <span id="data"></span></p>

<svg class="chart" width="120" height="500">
    <rect></rect>
    <rect></rect>
    <rect></rect>
    <rect></rect>
    <rect></rect>
    <rect></rect>
</svg>

<script>
var data = [4,8,15,16,23,42];
document.getElementById("data").innerHTML = data;
d3.selectAll("rect")
	.data(data)
    .attr("width",19)
    .attr("height",function(d) { return 10*d; })
    .attr("x",function(d,i) { return 20*i; })
    .attr("y",function(d) { return 420 - 10*d; });
</script>

</body></html>


### Markdown


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

#### Bold

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tylerwatkins101/cs498-visualization-project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
