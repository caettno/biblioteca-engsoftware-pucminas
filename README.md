# Biblioteca de Engenharia de Software

![Biblioteca de Engenharia de Software](assets/banner.png)

## Visão geral

Repositório público que funciona como uma grande biblioteca para reunir os materiais didáticos do curso de Engenharia de Software feito de aluno para aluno. A ideia é que estudantes atuais e futuros tenham, em um só lugar, atividades, livros, apostilas, provas e outros conteúdos de cada disciplina, organizados por período e por ano.

## Como o repositório está organizado

O repositório é dividido em **8 pastas, uma para cada período** do curso. Dentro de cada período há uma pasta por disciplina, e dentro dela uma pasta por ano em que o conteúdo foi adicionado. Cada ano reúne quatro tipos de conteúdo:

| Pasta        | O que vai nela                                          |
| ------------ | ------------------------------------------------------- |
| `atividades` | Listas de exercícios, trabalhos, projetos e práticas    |
| `materiais`  | Livros, apostilas, slides, resumos e links de apoio     |
| `avaliacoes` | Provas, gabaritos e demais avaliações                   |
| `outros`     | [Opcional: qualquer conteúdo que não se encaixe acima]  |

Exemplo de caminho completo:

```text
.
├── 01-periodo/
│   ├── introducao-a-algoritmos/
│   │   └── 2026/
│   │       ├── atividades/
│   │       ├── materiais/
│   │       └── avaliacoes/
│   └── [outra-disciplina]/
├── 02-periodo/
├── 03-periodo/
├── 04-periodo/
├── 05-periodo/
├── 06-periodo/
├── 07-periodo/
├── 08-periodo/
├── assets/
│   └── banner.png
└── README.md
```

## Períodos

| Período | Pasta                            |
| ------- | -------------------------------- |
| 1º      | [`01-periodo`](01-periodo/)      |
| 2º      | [`02-periodo`](02-periodo/)      |
| 3º      | [`03-periodo`](03-periodo/)      |
| 4º      | [`04-periodo`](04-periodo/)      |
| 5º      | [`05-periodo`](05-periodo/)      |
| 6º      | [`06-periodo`](06-periodo/)      |
| 7º      | [`07-periodo`](07-periodo/)      |
| 8º      | [`08-periodo`](08-periodo/)      |

## Como contribuir

1. Faça um fork do repositório (ou peça acesso de colaborador).
2. Encontre a pasta do período e da disciplina. Se ela ainda não existir, crie.
3. Dentro da disciplina, use a pasta do ano atual (por exemplo, `2026`) e coloque o arquivo em `atividades`, `materiais` ou `avaliacoes`.
4. Use nomes de pastas e arquivos em minúsculas, sem acentos e com hífen no lugar de espaço (por exemplo, `introducao-a-algoritmos`).
5. Abra um Pull Request descrevendo o que foi adicionado.


## Mantenedores

- Igor Caetano — @caettno

## Tecnologias

- Markdown
- Git e GitHub
