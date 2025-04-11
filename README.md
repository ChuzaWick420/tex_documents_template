# Tex Documents Template
This project is just a template for generating documents according to my personal preferences.
You may edit the following variables to change color scheme.

## Control parameters


<details>
    <summary>Code Blocks</summary>
    <ul>
        <li><code>PreprocessorColor</code></li>
        <li><code>ImportedColor</code></li>
        <li><code>DataTypeColor</code></li>
        <li><code>NormalColor</code></li>
        <li><code>OperatorColor</code></li>
        <li><code>AttributeColor</code></li>
        <li><code>BuiltinColor</code></li>
        <li><code>KeywordColor</code></li>
        <li><code>DecimalColor</code></li>
        <li><code>FloatColor</code></li>
        <li><code>CharColor</code></li>
        <li><code>SpecialCharColor</code></li>
        <li><code>CommentColor</code></li>
        <li><code>ControlFlowColor</code></li>
        <li><code>StringColor</code></li>
    </ul>
</details>

<details>
    <summary>Headings</summary>
    <ul>
        <li><code>SectionColor</code></li>
        <li><code>SubSectionColor</code></li>
        <li><code>SubSubSectionColor</code></li>
        <li><code>ParagraphColor</code></li>
        <li><code>SubParagraphColor</code></li>
    </ul>
</details>

<details>
    <summary>Miscellaneous</summary>
    <ul>
        <li><code>PageColor</code></li>
        <li><code>TextColor</code></li>
        <li><code>linkcolor</code></li>
    </ul>
</details>

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
![img_4](assets/ss_4.png)
![img_5](assets/ss_5.png)
![img_6](assets/ss_6.png)
![img_7](assets/ss_7.png)
