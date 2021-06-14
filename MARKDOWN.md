# TÍTULOS:
> Para criar um título, basta digitar uma cerquilha `#` antes do texto do título.<br>
> Cada `#` representa um nível de título:

`#` = > Título de nível 1 | `##` => Título de nível 2 | `###` => Título de nível 3
---|---|---
`####` => Título de nível 4 | `#####` => Título de nível 5 | `######` => Título de nível 6

# FORMATAÇÃO DE TEXTO:
## NEGRITO:
> Para deixar um texto negrito, deve-se envolvê-lo entre um duplo par de asteriscos ou de underlines: `**texto**` ou `__texto__`

`**Negrito**` => **Negrito** | `__Negrito__` => __Negrito__
---|---

## ITÁLICO:
> Para deixar um texto itálico, deve-se envolvê-lo entre um par de asteriscos ou de underlines: `*texto*` ou `_texto_`

`*Itálico*` => *Itálico* | `_Itálico_` => _Itálico_
---|---

## NEGRITO E ITÁLICO:
> Para deixar um texto negrito e itálico, deve-se envolvê-lo entre um par de asteriscos, envolto em um duplo par de underlines: `__*texto*__`

`__*Negrito e Itálico*__` => __*Negrito e Itálico*__
---|

## RISCADO:
> Para deixar um texto riscado, deve-se envolvê-lo entre um duplo par de tios: `~~texto~~`
`~~Riscado~~` => ~~Riscado~~
---|

# LINHA HORIZONTAL:
> Para criar uma linha horizontal, basta digitar 3 vezes o traço: `---`
---

# LISTAS:
## ORDENADA:
> Para criar uma lista ordenada, basta digitar qualquer número, seguido de um ponto, antes dos itens: 
```
1. Item;
1. Item;
   1. Subitem
   1. Subitem
1. Item.
```
> A lista vai ficar em ordem crescente, como no exemplo baixo:
1. Item;
1. Item;
   1. Subitem
   1. Subitem
1. Item.

## NÃO ORDENADA:
### TIPO 1:
> Para criar uma lista sem necessidade de ordem, basta digitar um asterisco `*` antes dos itens:
```
* Item;
* Item;
   * Subitem
   * Subitem
* Item.
```
> Resultado:
* Item;
* Item;
   * Subitem
   * Subitem
* Item.

### TIPO 2:
> Também é possível criar uma lista não ordenada digitando um traço `-` antes dos itens:
```
- Item;
- Item;
   - Subitem;
   - Subitem;
- Item.
```
> Resultado:
- Item;
- Item;
   - Subitem;
   - Subitem;
- Item.

## LISTA DE TAREFAS:
> Para criarmos uma tarefa, devemos digitar o seguinte: `- [ ] Descrição da tarefa.`
- [ ] Agendar reunião.

> Quando quisermos indicar que uma tarefa já foi realizada, substituiremos o espaço entre os colchetes por um "x":<br>`- [x] Tarefa realizada.`
- [x] Tarefa realizada.

> Assim podemos montar uma lista de tarefas que indique o status de cada uma:
- [x] Agendar reunião;
- [ ] Organizar as paltas.

## IMAGEM:
> Para adicionarmos uma imagem, digitamos o seguinte: `![Descrição da imagem](url da imagem)`<br>
Exemplo: `![Logo do Github](https://github.githubassets.com/images/modules/logos_page/Octocat.png)`

![Logo do Github](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

## LINK:
> Para adicionarmos um link, utilizamos o seguinte: `[Texto do link](url do link)`<br>
Exemplo: `[Veja meu perfil do Github](https://github.com/juniortex)`

[Veja meu perfil do Github](https://github.com/juniortex)

## TABELA:
> Use o código a seguir para criar tabelas:
```
COLUNAS: | A | B | C
---|---|---|---
LINHA 1 | A1 | B1 | C1
LINHA 2 | A2 | B2 | C2
LINHA 3 | A3 | B3 | C3
```
### Exemplo:
Num | Nome | Nota
---|---|---
1 | João | 8,5
2 | Maria | 10,0
3 | José | 9,0

## CÓDIGO:
Use as crases ` `` ` para envolver o código desejado.

### Exemplo:
O código `document.getElementById()` pertence a linguagem JavaScript.

## CÓDIGO PRÉ-FORMATADO:
Use as crases triplas para envolver um código de várias linhas: ` ```código``` `

### Exemplo:
O código abaixo, pertence ao JavaScript:
```
num = Int(input('Digite o valor:'))
    if num % 2 == 0:
    print(f'O valor {num} é PAR')
    else:
    print(f'O valor {num} é IMPAR')
```

## EMOJIS:
Para usar emojis, deve-se colocar o nome do emoji entre dois pontos: `:nome_do_emoji:`

### Exemplos:
`:smiling_face_with_three_hearts:` => :smiling_face_with_three_hearts:<br>
`:smiling_face_with_three_hearts:` => :smiling_face_with_three_hearts:<br>
`:wink:`=> :wink:

Mais emojis neste [link.](https://github.com/ikatyang/emoji-cheat-sheet)

## MARCAR PERFIS:
Use `@user` para marcar um perfil.

### Exemplo: @microsoft
> OBS: _parece que só funciona em issues..._

## REPLY (RESPOSTA):
Use o sinal de maior `>` + `a mensagem que você petende responder` para marcá-la e respondê-la.

### Exemplo:
> Mensagem...

Sua resposta.

[Acessar o Manual do Markdown do Guanabara.](https://github.com/gustavoguanabara/git-github/tree/master/manuais-PDF)