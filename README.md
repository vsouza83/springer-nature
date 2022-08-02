# Article Format Template (AFT)

<!-- ALL THE BELOW SHOULD BE IN YOUR README -->

This is a Quarto template that assists you in creating a manuscript for Article Format Template journals. You can learn more about producing LaTeX output for Springer_Nature journals in [[https://www.springernature.com/gp/authors/campaigns/latex-author-support]]

## Creating a New Article

You can use this as a template to create an article for an AFT journal. To do this, use the following command:

```quarto use template quarto-journals/article-format-template```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto install extension quarto-journals/article-format-template```

## Usage 

To use the format, you can use the format names `aft-pdf` and `aft-html`. For example:

```quarto render article.qmd --to aft-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  aft-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://quarto-journals.github.io/article-format-template/>.

## Format Options

This format does not have specific format option. Include documentation of such option otherwise. See <https://github.com/quarto-journals/elsevier#format-options> for an example.
