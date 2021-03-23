# Linguagem MarkDown

## Onde usamos o MarkDown

Usamos **MarkDown**:

* README.md
* Isseus
* Pull request
* arquivos com extensão ".md"
***
## Trabalhando com títulos

se colocar uma \# Título 1

**Exemplo:**

# Titulo 1

se colocar duas \#\# Título 2

**Exemplo**:

## Titulo 2

se colocar três \#\#\# Título 3

**Exemplo**:

### Titulo 3

se colocar quatro \#\#\#\# Título 4

**Exemplo**:

#### Titulo 4

se colocar cinco \#\#\#\#\# Título 5

**Exemplo**:

##### Titulo 5

se colocar seis \#\#\#\#\#\# Título 6

**Exemplo**:

###### Titulo 6
***

## Como deixar em negrito

Podemos usar 2 \*\* ou 2 \_\_ no início e no fim, da frase ou palavra.

**Exemplo:**

`Olá, **Bom dia!** ou Olá, __Bom dia!__`

**Resultado**

Olá, **Bom dia!** ou Olá, __Bom dia!__

## Como deixar em itálico

Podemos usar _um \* ou uma \_ no início e no fim, da frase ou palavra_.

**Exemplo:**

`Olá, #Bom dia!# ou Olá, _Bom dia!_`

**Resultado**

Olá, *Bom dia!* ou Olá, _Bom dia!_

## Como deixar com risco no meio

Podemos usar dois \~\~ no início e no fim, da frase ou palavra.

**Exemplo:**

`Olá, ~~Bom dia!~~`

**Resultado**

Olá, ~~Bom dia!~~

## Como criar linha

Pode-se criar linha com 3 \-\-\- ou \*\*\*

**Exemplo:**

`---` ou `***`

__resultado__

---
ou
***

## Criando listas

### como criar lista numerada

Pode-se criar lista colocando, um número e um .:

**Exemplo:**

```
1. item 1
1. item 2
2. item 3
```

__Resultado__

1. item 1
1. item 2
2. item 3

### Inserindo subitem na lista numerada

Pode-se criar subitens na lista numerada, inserindo 3 (espaços), seguidos de um número e um ponto.

**Exemplo:**

```
1. item 1
   1. subitem 1
1. item 1
   1. subitem 1
   1. subitem 2
```

__Resultado:__

1. item 1
   1. subitem 1
1. item 1
   1. subitem 1
   1. subitem 2

### Como criar lista demarcada

Pode-se criar uma lista demarcada, inserindo um \* ou \-.

**Exemplo:**

```
* item 1
* item 2
   - item 1
   - item 2
```

__Resultado:__

* item 1
* item 2
   - item 1
   - item 2

### Como criar lista de tarefas

Pode-se criar uma lista de trarefas, colocando um \- um (espaço),  abre e fecha \[(espaço)\], e para marcar como feito é só colocar um x dentro do \[x\].

**Exemplo:**

```
- [x] Criar repositório git_github
- [x] Criar arquivo README.md
- [x] Criar arquivo markdown.md
- [x] Continuar do Videoaula do Guia da Linguagem Markdown – Curso de Git e GitHub - 21:49
- [ ] Ir alimentando o arquivo markdown.md
```

__Resultado__

- [x] Criar repositório git_github
- [x] Criar arquivo README.md
- [x] Criar arquivo markdown.md
- [x] Continuar do Videoaula do Guia da Linguagem Markdown – Curso de Git e GitHub - 21:49
- [ ] Ir alimentando o arquivo markdown.md

## Inserindo imagens

Pode-se inserir imagens, colocando uma \!\[descrição\]\(URL\).

```
![GitHub 1](https://github.com/carvalhoh/git_github/blob/main/img/github-150x150.jpg?raw=true)
```

**Resultado:**

![GitHub 1](https://github.com/carvalhoh/git_github/blob/main/img/github-150x150.jpg?raw=true)

## Inserindo links

Pode-se inserir links, \[palavra que será mostrada\]\(URL\).

### Minha midias

**Exemplo:**

```
[Meu GitHub](https://github.com/carvalhoh/)

[Meu linkedin](https://www.linkedin.com/in/carvalhohebert/)
```

**Resultado:**

[Meu GitHub](https://github.com/carvalhoh/)

[Meu linkedin](https://www.linkedin.com/in/carvalhohebert/)

## Criando tabelas

Pode-se criar tabelas, inserindo:
cabeçalho: nome \| nome2 \| nome3 ...
Linha: \-\-\-\|\-\-\-\|\-\-\- ...
conteúdo: teste1 \| teste2 \| teste3 ...

**Exmplo do código:**

```
Código | Nome | Nota
---|---|---
1 | Hebert | 9,3
2 | Taty | 9,3
3 | Bernardo | 9,0
4 | Júlia | 9,0
```

**Resultado:**

Código | Nome | Nota
---|---|---
1 | Hebert | 9,3
2 | Taty | 9,3
3 | Bernardo | 9,0
4 | Júlia | 9,0

## Inserindo comandos

Pode-se inserir códigos, \`Código de uma linha\`,
\`\`\`
Para
mais
de
uma
linha
\`\`\`

**Exemplo:**

```
`código de uma linha`
```

**Resultado:**

`código de uma linha`


**Exemplo:**

\`\`\`
Para
mais
de
uma
linha
\`\`\`

**Resultado**

```
Para
mais
de
uma
linha
```

## Inserindo emojis

Pode-se inserir emojis, colocando \:nome do emoji\:.

**Exemplo:**

`Eu gosto de livros :books:`

**Resultado:**

Eu gosto de livros :books:

## inserindo citações

Pode-se inserir citações, inserindo um sinal de maior \> na frente da frase em cada linha.

**Exemplo:**

```
Como **Steve Jobs** disse uma vez:

> *Decidir* o que não fazer é tão
> _Importante_ quanto decidir
> o que fazer.
```

**Resultado:**

Como **Steve Jobs** disse uma vez:

> *Decidir* o que não fazer é tão
> _Importante_ quanto decidir
> o que fazer.
