# pandoc-gfm-pdf.css

The purpose of [pandoc-gfm-pdf.css](./pandoc-gfm-pdf.css) is to provide the most minimal amount of CSS to create a PDF in the style of [Github Flavored Markdown](https://github.github.com/gfm/) (GFM).

The goal is to look "good enough" while having the least amount of lines of code as possible. **It's not meant to be a 100% faithful representation of GFM.**

## Prerequisites

- [Pandoc](https://pandoc.org/installing.html)
- [WeasyPrint](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#installation)

## Usage

Download [pandoc-gfm-pdf.css](https://raw.githubusercontent.com/stefin0/pandoc-gfm-pdf.css/refs/heads/main/pandoc-gfm-pdf.css)

```bash
wget https://raw.githubusercontent.com/stefin0/pandoc-gfm-pdf.css/refs/heads/main/pandoc-gfm-pdf.css
```

Convert your markdown file, using pandoc, to a PDF.

```bash
pandoc -f gfm --pdf-engine=weasyprint --css=./pandoc-gfm-pdf.css -o output.pdf input.md
```

## Example output

You can expect your output PDF to look similar to [output.pdf](./output.pdf)

https://github.com/user-attachments/assets/9ee47b94-cf17-4f3e-bf1a-d1f306d4be54
