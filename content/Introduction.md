---
abstract: |
    Decision Tree is a commonly used algorithm in **Supervised Learning**, for **Classification** and **Regression** tasks. It has the shape of a flowchart, each branch represents a question, and depends on your answer, you move on to the next step. It breaks downs complex dataset into a more easy-to-interpret structures
---

# Introduction to Decision Tree

## A brief overview of Machine Learning:
Humans acquire knowledge about the world around them through past experiences, whereas a computer can only follow instructions given by humans. But what if we can train machines to do what we can do at a much faster rate, by learning existing data as input? This is, to some extent, the definition of Machine Learning: the ability to learn, grow, and adapt of machines when exposed to unseen data.

Machine Learning iis commonly divided into three main categories: Supervised Learning, Unsupervised Learning, and Reinforcement Learning, each serves a different purpose and/or task.
![alt text](figures/MLoverview.png)

**cite with doi**
- `[@doi:10.25080/hwcj9957]` resulting in [@doi:10.25080/hwcj9957]
- `@doi:10.25080/hwcj9957` resulting in @doi:10.25080/hwcj9957

**cite from bib-file**
- `{cite:t}`jupyter2025`` resulting in {cite:t}`jupyter2025`
- `{cite:p}`jupyter2025`` resulting in {cite:p}`jupyter2025`


## Background
Jupyter Book has been rebuild with the intend to export content in multiple output formats including HTML, PDF and docx. {numref}`Figure {number} <fig-diagram>` provides this idea.

```{figure} figures/diagram.*
:label: fig-diagram
:alt: Some figure

The myst engine allows Jupyter Notebook, markdown and even tex files to be converted to multiple output formats.
```

As exporting to different formats is possible, it is not always desired. Some content should only be visible in the HTML version, and some content only need to be included in the PDF version. You can use blocks like `+++{"no-pdf":true}` to enable this, as shown below where the figure is seen in the HTML version but not in the PDF version.

+++{"no-pdf":true}
```{figure} figures/delft.*
:label: fig-delft
:alt: picture of the TUD

A figure that is in the website but not in the PDF version.
```
+++

Moreover, sometimes you want to have content [only showing up](xref:myst-guide/creating-pdf-documents#including-content-with-specific-exports) in the pdf, if you use Typst you can use of a block `+++{raw:typst}` and for LaTeX `+++{raw:latex}`. 
