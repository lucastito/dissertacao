# Dissertação — apoio computacional à epidemiologia

Fontes em LaTeX da dissertação **“Apoio Computacional ao Estudo Epidemiológico de Doenças Infecciosas Emergentes”**, de Lucas de Souza Tito.

## Sobre o trabalho

A pesquisa investiga como técnicas de ciência de dados e e-Science podem apoiar o processamento, a integração, a consulta e a visualização de dados epidemiológicos. A avaliação utiliza dados laboratoriais para estudar infecções emergentes, incluindo análises relacionadas ao vírus Zika.

## Organização

- `dissertação.tex`: documento principal.
- `cap0.tex` a `cap6.tex`: elementos iniciais e capítulos da dissertação.
- `apendice.tex`: conteúdo complementar.
- `bibliografia.bib`: referências bibliográficas.
- arquivos de classe e estilo: formatação acadêmica baseada no modelo utilizado.
- `tese.pdf`: versão compilada disponível para leitura.

Os capítulos cobrem introdução, fundamentação teórica, abordagem proposta, avaliação experimental, trabalhos relacionados, conclusão e trabalhos futuros.

## Como compilar

É necessária uma distribuição LaTeX com suporte a BibTeX. A partir da raiz:

```bash
pdflatex dissertação.tex
bibtex dissertação
pdflatex dissertação.tex
pdflatex dissertação.tex
```

Em sistemas nos quais o terminal ou a ferramenta não lida bem com acentos em nomes de arquivos, use um editor LaTeX que permita selecionar `dissertação.tex` como documento principal.

## Estado do repositório

Este é um registro acadêmico e histórico. A versão em PDF permite consultar o trabalho sem reconstruir o ambiente LaTeX original.

