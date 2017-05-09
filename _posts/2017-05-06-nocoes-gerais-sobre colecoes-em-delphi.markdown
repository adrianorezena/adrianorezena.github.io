---
layout: post
title:  "Noções gerais sobre coleções em Delphi"
date:   2017-05-05 22:21:53 -0300
categories: jekyll update
---

Usadas amplamente em qualquer tipo de projeto, as listas evoluíram bastante nas últimas versões do Delphi, principalmente com a adição do Generics.

Hoje temos vários tipos de listas. Abaixo temos uma tabela com os tipos mais comuns e suas principais características:

| Tipo | Descrição |
|-------|---------|
| **Collection** | É um grupo de itens sem qualquer ordem. Itens podem ser inseridos ou removê-los, mas não ordenados. |
| **Dictionary** | Conhecida também como "hash table" por gerar um hash da chave para otimizar sua velocidade, representa uma coleção de dados em par, do tipo chave-valor, onde tanto a chave como o valor podem ser de qualquer tipo. |
| **List** | Um List é uma estrutura de dados que semelhante ao array, apesar de agregar muito mais funcionalidades que um array. Possui um índice que começa de zero e que permite "encontrar" cada item da lista. Os itens podem ser ordenados e a ordem é você quem define. |
| **Queue** | Uma queue é uma estruta de dados do tipo FIFO (First In, First Out), onde os primeiros itens que foram adicionados, são os primeiros a sair. |
| **Stack** | Uma stack é uma estrutura de dados do tipo FILO (First In, Last Out), onde como o próprio nome diz, é uma pilha. É fácil assemelhar isto a uma pilha de pratos. O último prato que foi colocado sobre a pilha, tem que ser o primeiro prato a sair. |


Todos esses tipos de listas, podemos encontrar na unit System.Generics.Collections.

Os tipos mais comuns são:
* TList<T>
* TQueue<T>
* TStack<T>
* TDictionary<TKey, TValue>
* TObjectList<T>
* TObjectQueue<T>
* TObjectStack<T>
* TObjectDictionary<TKey, TValue>
* TThreadList<T>
* TThreadedQueue<T>

Todos os tipos acima, com exceção dos últimos dois, podem ser iterados através de um for..in.

Nos próximos posts teremos exemplos de cada tipo citado acima.




[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
