# Springer-Nature

This is a Quarto template that assists you in creating a manuscript for Springer-Nature journals. You can learn more about producing LaTeX output for Springer-Nature journals in https://www.springernature.com/gp/authors/campaigns/latex-author-support.

## Creating a New Article

You can use this as a template to create an article for a Springer-Nature journal. To do this, use the following command:

```quarto use template quarto-journals/springer-nature```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto install extension quarto-journals/springer-nature```

## Usage 

To use the format, you can use the format names `springer-nature-pdf` and `springer-nature-html`. For example:

```quarto render article.qmd --to springer-nature-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  springer-nature-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://quarto-journals.github.io/springer-nature/>.

## Format Options

The Springer-Nature format supports a number of options for customizing the format and appearance of the document. Specify these under the XXXXXX key.