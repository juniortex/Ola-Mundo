# MARKDOWN
# Título 1 => `# Título 1`
## Título 2 => `## Título 2`
### Título 3 => `### Título 3`

## NEGRITO:
`**Negrito**` => **Negrito**

`__Negrito__` => __Negrito__

## ITÁLICO:
`*Itálico*` => *Itálico*

`_Itálico_` => _Itálico_

## NEGRITO E ITÁLICO:
`__*Negrito e Itálico*__` => __*Negrito e Itálico*__

## RISCADO:
`~~Riscado~~` => ~~Riscado~~

## LINHA HORIZONTAL:
`*** ou ---`
> OBS: _parece que só funciona em issues..._

## LISTAS:
### NUMERADA:
```
1. Item;
1. Item;
   1. Subitem
   1. Subitem
1. Item.
```
1. Item;
1. Item;
   1. Subitem
   1. Subitem
1. Item.

### INUMERADA:
#### TIPO 1:
```
* Item;
* Item;
   * Subitem
   * Subitem
* Item.
```
* Item;
* Item;
   * Subitem
   * Subitem
* Item.

#### TIPO 2:
```
- Item;
- Item;
   - Subitem;
   - Subitem;
- Item.
```
- Item;
- Item;
   - Subitem;
   - Subitem;
- Item.

## LISTA DE TAREFAS:
```
- [ ] Tarefa pendente;
- [ ] Tarefa pendente;
- [x] Tarefa completa.
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
Use as crases para envolver o código desejado: ` `código` `

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
> OBS: _Também prece que só funciona em issues..._

## REPLY (RESPOSTA):
> Mensagem...
<br>Sua resposta.

[Acessar o Manual do Markdown do Guanabara.](https://github.com/gustavoguanabara/git-github/tree/master/manuais-PDF)