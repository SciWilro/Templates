### Templates : Overview

```markdown

## Markdown

### Footer for blogs

Copy [footer.html](https://github.com/SciWilro/Templates/Markdown/footer.html) to the same directory of .rmd file. To display footer at the end of the document, add the following to the YAML header:


---
title: "Your title"
output:
  html_document:
    includes:
      after_body: footer.html
---


Source
: <https://github.com/holtzy/Pimp-my-rmd>

***

```

<!--
### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SciWilro/Templates/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
-->
