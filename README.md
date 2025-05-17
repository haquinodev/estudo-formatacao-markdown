# Estudos sobre Formatação em Markdown
> Fonte  das anotações: Curso Dio _ Formação Github Certification - Professora: Aline Antunes 

<!--Cabeçalhos-->
## Cabeçalhos
#### Usa-se a # antes do texto do cabeçalho. O tamalho do cabeçalho é definido pela quantidade de #, quanto mais # juntas (##, ###, ####, #####, ######), menor serão os caracteres do texto. Essa escala vai até seis hashtags seguidas.

Exemplo:
---------------------

# Título 1 
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6


## Negrito e Itálico
#### O negrito é representado usando dois asteriscos \*\* texto que aparecerá em negrito, seguido por dois asteriscos novamente \*\*

##### Exemplo:
\*\*negrito\*\* -> **negrito** 

#### O itálico é representado usando um asterisco \* texto que aparecerá em itálico, seguido por um asterisco novamente \*

##### Exemplo:
\*Itálico\* -> *Itálico*


## Listas e Sublistas
<!--LIstas e Sublistas-->
### Lista Não-ordenada:
- Lista 1
- Lista 2
  - Sublista 1
### Lista Ordenada:
1. Lista 1
2. Lista 2
   1. Sublista

## Links e Imagens

### Inserir Link
<!--Links-->
#### [Texto do Link](Link Usado)

Exemplo: [Praia de Ponta Negra](https://media.istockphoto.com/id/531165945/photo/ponta-negra-dunes-beach-in-city-of-natal-brazil.jpg?s=612x612&w=0&k=20&c=gVq0xULo1ldvK3Rc3-UCRk0IRzObpsfLt9A3YPV4DBc=)

### Inserir Imagem
<!--Inserir Imagem-->
#### ![texto da imagem](Link da Imagem)

Exemplo:
\![Natal/RN](https://www.viagenscinematograficas.com.br/wp-content/uploads/2018/03/Natal-RN-O-Que-Fazer-Praias-Capa-e1664501366980.jpg) -> <br>
![Natal/RN](https://www.viagenscinematograficas.com.br/wp-content/uploads/2018/03/Natal-RN-O-Que-Fazer-Praias-Capa-e1664501366980.jpg)

## Códigos
### Inserir Còdigos de uma linha:
<!-- Inserir Còdigos de uma linha-->
- Usamos um par de crases com a linha de código entre elas: <br>
\`linha de código\` -> `linha de código`<br>
\`system.out.println()\` -> `system.out.println()`

### Inserir Còdigos de bloco:
<!-- Inserir Códigos de bloco-->
- Usamos dois grupos de três crases com o texto compreendido entre eles. <br>
\`\`\` Bloco de Código \`\`\`  ->  ``` Bloco de Código ```


## Citações
<!--Citações-->

Sintaxe: <br>
\> Texto de Citações

> Texto de Citações
<!-- Linha-->
--------------------  

## Tabelas

### Colunas:
#### Escreva \|Coluna\| para delimitar as células da colunas.

- Exemplo: \| Coluna1 \| Coluna2 \| Coluna3 \|

### Linhas:
#### Escreva  \|-----------\| para definir as linhas.

- Exemplo: 
<!--Tabelas-->

| Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3 |
|-------------|-------------|-------------| 
|Texto 1      |Texto 2      |Texto 3      |
|Obs 1        |Obs   2      |Obs   3      |


## Lista de Tarefas

<!-- Lista de Tarefas-->
- [X] Tarefa 1
- [ ] Tarefa 2
- [X] Tarefa 3
- [ ] Tarefa 4
