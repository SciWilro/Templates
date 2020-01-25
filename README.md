### Templates : Overview



## Markdown

### Footer for blogs

Copy [footer.html](https://github.com/SciWilro/Templates/Markdown/footer.html) to the same directory of .Rmd file.  
To display footer at the end of the document, add the following to the YAML header:

```
---
title: "Your title"
output:
  html_document:
    includes:
      after_body: footer.html
---
```

Source <https://github.com/holtzy/Pimp-my-rmd>

### style.css

Copy [style.css](https://github.com/SciWilro/Templates/Markdown/style.css) to directory with .Rmd file.  
Edit YAML as follows:

```
---
title: "A document with a CSS included"
output:
  html_document:
    css: style.css
---
```

Currently includes:
+ Automatically add space before headers to make rendered document less cluttered.
+ Add style for **Tip** box `div.tip`
  Example 'Tip'

```
<div class = "tip"><strong class="">★ Tip</strong><p class="">
Here is a tip in a nice box
</p></div>
```

***

<!--
### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SciWilro/Templates/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
-->
