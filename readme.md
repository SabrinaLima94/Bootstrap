<h1 align="center"> Desenvolvimento web completo - Udemy</h1>
<h2 align="center">Bootstrap & Design responsivo </h2>

<div align="center">
<img src="./img/capa.png" width="20%"></div>

<h3 id="indice-menu">Índice</h3>

1. <a href="#formatacaotexto">Formatações de textos</a><br>

   1. <a href="#tag1">Display classes</a><br>
   2. <a href="#tag2">Parágrafo</a><br>
   3. <a href="#tag3">Parágrafo Monoespace</a><br>
   4. <a href="#tag4">Classes de estilo</a><br>
   5. <a href="#tag5">Transformação de textos</a><br>
   6. <a href="#tag6">Alinhamentos</a><br> 7.<a href="#tag7">Bloco de citação</a><br> 8.<a href="#tag8">Truncate</a><br> 9.<a href="#tag9">Listas</a><br>

2. <a href="#alinhamento">Alinhamento de textos</a><br>

3. <a href="#elementos-flutuantes">Elementos flutuantes</a><br>

4. <a href="#cores-background">Cores & Backgrounds</a><br>

5. <a href="#margin-padding">Margin & Padding</a><br>

6. <a href="#tamanhos-bordas">Tamanhos e bordas</a><br>

7. <a href="#media-queries">Media queries</a><br>

8. <a href="#botoes">Botões</a><br>

9. <a href="#barra-nav">Barra de navegação</a><br>

10. <a href="#listas">Listas</a><br>

11. <a href="#formularios">Formulários</a><br>

12. <a href="#input-group">Input Group</a><br>

13. <a href="#alertas">Alertas & Barra de progresso</a><br>

14. <a href="#tabelas-paginacao">Tabelas e paginação</a><br>

15. <a href="#cards">Cards</a><br>

16. <a href="#jumbotron">Jumbotron & Alinhamento de imagens</a><br>

17. <a href="#icones">Ícones</a><br>

18. <a href="#grid">Grid</a><br>

19. <a href="#flexbox">Flexbox</a><br>

20. <a href="#wrap">Margin & Wrap</a><br>

<h2 id="formatacaotexto" align="center">Formatações de texto</h2>

<h4 id="tag1">1. Display classes</h4>

Possibilita destaque maior aos títulos onde é aplicado

_Exemplo:_

```html
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag2">2. Parágrafo</h4>

Destaca o parágrafo alterando sua formatação original

_Exemplo_

```html
<p class="lead">
  Lorem Ipsum is simply dummy text of the printing and typesetting industry
</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag3">3. Parágrafo Monospace</h4>

É um padrão de letras que era utilizado em máquina de escrever.
Deixa os caracteres com a mesma largura.

_Exemplo_

```html
<p class="text-monospace">
  Lorem Ipsum is simply dummy text of the printing and typesetting industry
</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag4">4. Classes de estilo</h4>

a) Texto em negrito

```html
<p class="font-weight-bold">Texto Negrito</p>
```

b) Texto normal

```html
<p class="font-weight-normal">Texto Normal</p>
```

c) Texto itálico

```html
<p class="font-italic">Texto Itálico</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag5">5. Transformação de textos</h4>

a) Letras maiúsculas

```html
<p class="text-uppercase">letras maiúculas</p>
```

b) Letras minúsculas

```html
<p class="text-lowercase">LETRAS MINÚSCULAS</p>
```

c) Primeira letra maiúscula

```html
<p class="text-capitalize">primeira letra maiúscula</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag6">6. Alinhamentos</h4>

a) À direita

```html
<p class="text-right">Direita</p>
```

b) À esquerda

```html
<p class="text-left">Esquerda</p>
```

c) Centralizado

```html
<p class="text-center">Centralizado</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag7">7. Bloco de citação</h4>

A tag `blockquote` cria um bloco de citação, podendo ser aplicado juntamente a `class` com o mesmo nome.

_Exemplo_

```html
<blockquote class="blockquote">
  <p>Esse é um bloco de citação</p>
</blockquote>
```

É possível também utilizar a class ´blockquote-footer´, que dá uma formatação ao bloco no rodapé.

A tag `cite` possibilita indicar um autor

_Exemplo_

```html
<blockquote class="blockquote text-right">
  <p>
    Lorem Ipsum is simply dummy text of the printing and typesetting industry.
  </p>
  <footer class="blockquote-footer">
    por
    <cite>Sabrina Lima</cite>
  </footer>
</blockquote>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag8">8. Truncate</h4>

É utilizada para "truncar" ou cortar partes do texto. Quando aplicado, por exemplo, em um parágrafo, ao expandir a tela o texto irá aparecer mais e, ao passar o cursor em cima, aparecerá o texto completo _(este recurso está disponível apenas para Safari)_.

_Exemplo_

```html
<p class="text-truncate">
  Lorem Ipsum is simply dummy text of the printing and typesetting industry.
</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag9">9. Listas</h4>

a) Listas sem estilo

_Exemplo_

```html
<ul class="list-unstyled">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

b) Listas inline (na mesma linha)

_Exemplo_

```html
<ul class="list-inline">
  <li class="list-inline-item">Item 1</li>
  <li class="list-inline-item">Item 2</li>
  <li class="list-inline-item">Item 3</li>
</ul>
```

_Obs: Deve ser aplicado em todos os elementos dentro da lista_

<a href="#indice-menu">Voltar ao índice</a>
