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
- `linkcolor`

## Prerequisites
- [Pandoc](https://pandoc.org/installing.html)
- A TeX distribution (either of the following)
    - [TeX live](https://www.tug.org/texlive/)
    - [MiKTeX](https://miktex.org/)

## Usage
The `<output>` can be `*.pdf` or `*.tex`.

> [!CAUTION]
> For the images, use `xelatex` engines. The other engines like `pdflatex` does not handle images effectively.

```bash
pandoc "input.md" -o <output> --template=template.tex --pdf-engine=xelatex
```

## Screenshots
![img_1](assets/ss_1.png)
![img_2](assets/ss_2.png)
![img_3](assets/ss_3.png)
![img_4](assets/ss_4.png)
![img_5](assets/ss_5.png)
![img_6](assets/ss_6.png)
![img_7](assets/ss_7.png)
