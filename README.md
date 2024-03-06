<p align="center">
  <img src="src/images/logo.jpg" width="120px" height="120px">
  <h3 align="center"><b>Acervo da Computação</b></h3>
  <p align="center"><i>Acervo de materiais relacionados ao curso de Ciência da Computação do IFCE. </i></p>

---

### Índice
- [Introdução]()
- [Organização do Repositório]()
- [Como Contribuir]()

---

### Introdução

O objetivo desse repositório é servir como acervo de materiais relacionados ao curso de Ciência da Computação do IFCE, campus Maracanaú, contendo slides, livros, provas, trabalhos, e quaisquer outros materiais que possam servir de apoio para os estudantes. 

---

### Organização do Repositório 

O repositório é organizado em duas *branches*, a *main* e a *develop*. A *branch* *main* armazena o histórico de versionamento oficial do repositório, enquanto a *branch* *develop* serve como uma *branch* de integração para novos materiais que serão adicionados no acervo e em algum momento serão mesclados ou associados à main. 

A raiz do repositório deve conter apenas pastas com o nome do conteúdo que se encontrará dentro da pasta. Ex.:

```
├── Cadeiras
├── Fluxograma de Cadeiras
├── Programa de Unidade didática (PUD)
```

Se o conteúdo da pasta for abrangente, como é o caso da pasta *Cadeiras*, a pasta em questão deve delimitar seu conteúdo, o organizando em outras pastas. Ex.:

```
├── Cadeiras
│   └── Eletivas
│   └── S1
│   └── S2
│   ⋮ 
│   └── S8
```

As cadeiras são separadas por semestre (S1, S2, S3, ..., S8), com exceção das eletivas, que possuem uma pasta aparte. Dentro da pasta de cada semestre deve conter apenas pastas destinadas às cadeiras daquele respectivo semestre. Ex.:

```
├── Cadeiras
│   └── S1
│       ├── Cálculo I
│       ├── Circuitos Digitais
│       ├── Fundamentos de Programação
│       └── Matemática Discreta
```

Dentro da pasta da cadeira (ex.: Cálculo I), deve-se separar por pastas com o padrão de nomenclatura "Semestre - Nome do Professor" e, dentro de cada, organize os materiais por etapa. Ex.:

```
├── Matemática Discreta
│   └── 2023.2 - Cícero
│       ├── N1 - Lista de Exercícios para a Prova.jpeg
│       ├── N1 - Prova.jpeg
│       ├── N2 - Prova 1.jpeg
│       └── N2 - Prova 2.jpeg
```

Materiais que tendem a ser repetidos por vários semestres diferentes, como slides e livros, devem ficar em uma pasta separada. Ex.:

```
├── Laboratório de Programação
│   └── Slides - Daniel
│       ├── Linguagem C - Visão Geral.pdf
│       ├── Expressões em C.pdf
│       ├── Comandos de Controle de Programa.pdf
```

--- 

### Como Contribuir 
