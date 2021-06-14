# TÍTULOS:
> Para criar um título, basta digitar uma cerquilha `#` antes do texto do título.<br>
> Cada `#` representa um nível de título:

`# = > Título de nível 1`
`## => Título de nível 2`
`### => Título de nível 3`<br>
`#### => Título de nível 4`
`##### => Título de nível 5`
`###### => Título de nível 6`
<br>
# FORMATAÇÃO DE TEXTO:
## NEGRITO:
> Para deixar um texto negrito, deve-se envolvê-lo entre um duplo par de asteriscos ou de underlines: `**texto** ou __texto__`

Exemplos:<br>
`**Negrito**` => **Negrito**

`__Negrito__` => __Negrito__

## ITÁLICO:
`*Itálico*` => *Itálico*

`_Itálico_` => _Itálico_

# NEGRITO E ITÁLICO:
`__*Negrito e Itálico*__` => __*Negrito e Itálico*__

## RISCADO:
`~~Riscado~~` => ~~Riscado~~

## LINHA HORIZONTAL:
`*** ou ---`
> OBS: _parece que só funciona em issues..._

## LISTAS:
### ORDENADA:
Para criar uma lista ordenada, basta digitar qualquer número, seguido de um ponto: 
```
1. Item;
1. Item;
   1. Subitem
   1. Subitem
1. Item.
```
A lista vai ficar em ordem crescente, como no exemplo baixo:
1. Item;
1. Item;
   1. Subitem
   1. Subitem
1. Item.

### NÃO ORDENADA:
#### TIPO 1:
Para criar uma lista sem necessidade de ordem, basta digitar um asterisco `*` antes dos itens:
```
* Item;
* Item;
   * Subitem
   * Subitem
* Item.
```
Resultado:
* Item;
* Item;
   * Subitem
   * Subitem
* Item.

#### TIPO 2:
Também é possível criar uma lista não ordenada digitando um traço `-` antes dos itens:
```
- Item;
- Item;
   - Subitem;
   - Subitem;
- Item.
```
Resultado:
- Item;
- Item;
   - Subitem;
   - Subitem;
- Item.

## LISTA DE TAREFAS:
Use o código abaixo para criação de listas de tarefas:
```
- [ ] Tarefa pendente;
- [ ] Tarefa pendente;
- [x] Tarefa realizada. Quando quiser indicar que uma tarefa já foi realizada, substitua o espaço entre os colchetes por um "x".
```
- [ ] Tarefa pendente;
- [ ] Tarefa pendente;
- [x] Tarefa completa.

## IMAGEM:
Use ! + [Descrição da imagem] + (url da imagem)

### Exemplo:
`![Logo do Github](https://github.githubassets.com/images/modules/logos_page/Octocat.png)`
![Logo do Github](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

## LINK:
Use [Texto do link](url do link)

### Exemplo:
`[github.com/juniortex](https://github.com/juniortex)` => [github.com/juniortex](https://github.com/juniortex)

## TABELA:
Use o código a seguir para criar tabelas:
```
Num | Nome | Nota
---|---|---
1 | João | 8,5
2 | Maria | 10,0
3 | José | 9,0
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