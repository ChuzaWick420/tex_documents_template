# Tex Documents Template
This project is just a template for generating documents according to my personal preferences.
You may edit the following variables to change color scheme.

## Control parameters
- `SECTIONCOLOR`
- `SUBSECTIONCOLOR`
- `SUBSUBSECTIONCOLOR`
- `PARAGRAPHCOLOR`
- `SUBPARAGRAPHCOLOR`
- `PAGECOLOR`
- `TEXTCOLOR`

## Prerequisites
- [Pandoc](https://pandoc.org/installing.html)
- A TeX distribution (either of the following)
    - [TeX live](https://www.tug.org/texlive/)
    - [MiKTeX](https://miktex.org/)

## Usage
The `<output>` can be `*.pdf` or `*.tex`.
```bash
pandoc "input.md" -o <output> --template=template.tex --pdf-engine=xelatex
```

> [!CAUTION]
> For the images, use `xelatex` engine. The other engines like `pdflatex` will fail.

## Screenshots
![img_1](assets/ss_1.png)
![img_2](assets/ss_2.png)
![img_3](assets/ss_3.png)
