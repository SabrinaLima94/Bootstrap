<h1 align="center"> Desenvolvimento web completo - Udemy</h1>
<h2 align="center">Bootstrap & Design responsivo </h2>

<div align="center">
<img src="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png" width="20%"></div>

<h3 id="indice-menu">Índice</h3>

1. <a href="#formatacaotexto">Formatações de textos</a><br>

   1. <a href="#tag1">Display classes</a><br>
   2. <a href="#tag2">Parágrafo</a><br>
   3. <a href="#tag3">Parágrafo Monoespace</a><br>
   4. <a href="#tag4">Classes de estilo</a><br>
   5. <a href="#tag5">Transformação de textos</a><br>
   6. <a href="#tag6">Alinhamentos</a><br> 7.<a href="#tag7">Bloco de citação</a><br> 8.<a href="#tag8">Truncate</a><br> 9.<a href="#tag9">Listas</a><br>

2. <a href="#alinhamento">Alinhamento de textos</a><br>

   1. <a href="#tag10">Texto justificado</a><br>
   2. <a href="#tag11">Sufixos</a><br>
   3. <a href="#tag12">Convertendo elementos block para inline</a><br>
   4. <a href="#tag13">Convertendo elementos block para inline</a><br>
   5. <a href="#tag14">Elementos Inline-Block</a><br>

3. <a href="#elementos-flutuantes">Elementos flutuantes</a><br>

   1. <a href="#tag15">Float-left e Float-right</a><br>
   2. <a href="#tag16">Posicionamento fixo</a><br>
   3. <a href="#tag17">Float responsivo</a><br>
   4. <a href="#tag18">Sticky</a><br>

4. <a href="#cores-background">Cores & Backgrounds</a><br>

   1. <a href="#tag19">Classes para formatação de texto</a><br>
   2. <a href="#tag20">Formatação de links</a><br>
   3. <a href="#tag21">Backgrounds</a><br>

5. <a href="#margin-padding">Margin & Padding</a><br>

   1. <a href="#tag22">Margin</a><br>
   2. <a href="#tag23">Padding</a><br>

6. <a href="#tamanhos-bordas">Tamanhos e bordas</a><br>

   1. <a href="#tag24">Classes de largura</a><br>
   2. <a href="#tag25">Classes de altura</a><br>
   3. <a href="#tag26">Bordas</a><br>
   4. <a href="#tag27">Border radius</a><br>

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

- Possibilita destaque maior aos títulos onde é aplicado

_Exemplo:_

```html
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag2">2. Parágrafo</h4>

- Destaca o parágrafo alterando sua formatação original

_Exemplo_

```html
<p class="lead">
  Lorem Ipsum is simply dummy text of the printing and typesetting industry
</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag3">3. Parágrafo Monospace</h4>

- É um padrão de letras que era utilizado em máquina de escrever.
  Deixa os caracteres com a mesma largura.

_Exemplo_

```html
<p class="text-monospace">
  Lorem Ipsum is simply dummy text of the printing and typesetting industry
</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag4">4. Classes de estilo</h4>

- Texto em negrito

```html
<p class="font-weight-bold">Texto Negrito</p>
```

- Texto normal

```html
<p class="font-weight-normal">Texto Normal</p>
```

- Texto itálico

```html
<p class="font-italic">Texto Itálico</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag5">5. Transformação de textos</h4>

- Letras maiúsculas

```html
<p class="text-uppercase">letras maiúculas</p>
```

- Letras minúsculas

```html
<p class="text-lowercase">LETRAS MINÚSCULAS</p>
```

- Primeira letra maiúscula

```html
<p class="text-capitalize">primeira letra maiúscula</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag6">6. Alinhamentos</h4>

- À direita

```html
<p class="text-right">Direita</p>
```

- À esquerda

```html
<p class="text-left">Esquerda</p>
```

- Centralizado

```html
<p class="text-center">Centralizado</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag7">7. Bloco de citação</h4>

- A tag `blockquote` cria um bloco de citação, podendo ser aplicado juntamente a `class` com o mesmo nome.

_Exemplo_

```html
<blockquote class="blockquote">
  <p>Esse é um bloco de citação</p>
</blockquote>
```

- É possível também utilizar a class ´blockquote-footer´, que dá uma formatação ao bloco no rodapé.

- A tag `cite` possibilita indicar um autor

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

- É utilizada para "truncar" ou cortar partes do texto. Quando aplicado, por exemplo, em um parágrafo, ao expandir a tela o texto irá aparecer mais e, ao passar o cursor em cima, aparecerá o texto completo _(este recurso está disponível apenas para Safari)_.

_Exemplo_

```html
<p class="text-truncate">
  Lorem Ipsum is simply dummy text of the printing and typesetting industry.
</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag9">9. Listas</h4>

- Listas sem estilo

_Exemplo_

```html
<ul class="list-unstyled">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

- Listas inline (na mesma linha)

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

<h2 id="alinhamento" align="center">Alinhamento de textos</h2>

<h4 id="tag10">1. Texto justificado</h4>

_Exemplo_

```html
<p class="text-justify">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vestibulum
  elementum quam, a viverra ligula fringilla tempus. Ut tempor, dui eu semper
  aliquet, sem nisi pellentesque libero, suscipit porttitor risus magna vel
  lorem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus
  vestibulum elementum quam, a viverra ligula fringilla tempus. Ut tempor, dui
  eu semper aliquet, sem nisi pellentesque libero, suscipit porttitor risus
  magna vel lorem.
</p>
```

<h4 id="tag11">2. Sufixos</h4>

O bootstrap possibilita a criação de layouts responsivos, ou seja, que mudam de acordo com o dispositivo. Isto torna os sites mais adaptativos, criando exibições independente do tamanho da tela.

Existem sufixos que utilizamos para criar estas diferente exibições para cada dispositivo, são eles:

**a)** SM: Small - para dispositivos >= 576px;<br>
**b)** MD: Medium - para dispositivos >= 768px;<br>
**c)** LG: Large - para dispositivos >= 992px;<br>
**d)** XL: Extra Large - para dispositivos >= 1200px;<br>

Portanto, é possível definir alinhamentos específicos para diferentes tipos de tela.

_Exemplo de aplicação_

```html
<p class="text-sm-right">tela &gt;= 576px</p>
<!--Small-->

<p class="text-md-right">tela &gt;= 768px</p>
<!--Medium-->

<p class="text-lg-right">tela &gt;= 992px</p>
<!--Large-->

<p class="text-xl-right">tela &gt;= 1200px</p>
<!--Extra Large-->
```

- Para utilização deve ser aplicado: `"text-sufixoDaTela-alinhamento"`

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag12">3. Convertendo elementos block para inline</h4>

- A `class="d-inline"`transforma o elemento block em inline

_Exemplo:_

```html
<h1 class="bg-success d-inline">Lorem ipsum dolor</h1>

<p class="bg-success d-inline">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
</p>
```

_Obs: A tag `bg-success` e `bg-warning` aplicam um background na cor verde e amarelo respectivamente (foi utilizado apenas para demonstrar o comportamento dos elementos block e inline)_

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag13">4. Convertendo elementos online para block</h4>

- A `class="d-blok"`transforma o elemento inline em block

_Exemplo:_

```html
<span class="bg-success d-block">Lorem ipsum dolor 1</span>

<span class="bg-success d-block">Lorem ipsum dolor 2</span>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag14">5. Elementos Inline-Block</h4>

- A `class="d-inline-block"`torna o elemento híbrido.
- O elemento `inline` não permite aplicação de margin e padding superior, nem definir largura;
- O elemento `block` permite a aplicação de margin, padding superior e definir largura;
- O `inline-block` permite atribuição de margin superior, padding e largura (como block), porém também permite manter os elementos na mesma linha (como inline).

<a href="#indice-menu">Voltar ao índice</a>

<h2 id="elementos-flutuantes" align="center">Elementos flutuantes</h2>

<h4 id="tag15">1. Float-left e Float-right</h4>

_Exemplo_

```html
<div class="bg-success float-left">Float Left</div>

<div class="bg-warning float-right">Float Right</div>

<div class="float-none">Float None</div>
```

- A div com os elementos flutuantes não possui altura, e para corrigir utilizamos o `"clear: both"`;
- No bootstrap pode ser aplicado no "elemento pai" (parent, que abriga a div flutuante) a `class="clearfix"`

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag16">2. Posicionamento fixo</h4>

- É possível fixar um texto no início da página (`class="fixed-top"`) ou final (`class="fixed-bottom"`).

_Exemplo_

```html
<h1 class="bg-success fixed-bottom">Título do conteúdo fixo</h1>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag17">3. Float responsivo</h4>

- Podemos flutuar objetos para diferentes tamanhos de tela com `class="float-tamanhoDaTela-direcao"`;
- Só é possível utilizar o `float-left`ou `float-right` neste caso.

_Exemplo_

```html
<div class="float-sm-right">tela &gt;= 576px *</div>
<!--Small-->

<div class="float-md-right">tela &gt;= 768px *</div>
<!--Medium-->

<div class="float-lg-right">tela &gt;= 992px *</div>
<!--Large-->

<div class="float-xl-right">tela &gt;= 1200px *</div>
<!--Extra Large-->
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag18">4. Sticky</h4>

- A `class="sticky-top"` "gruda" uma lista no topo da página quando ela atinge o limite superior.

_Exemplo_

```html
<ul class="list-inline bg-warning sticky-top">
  <li class="list-inline-item">Item 1</li>
  <li class="list-inline-item">Item 2</li>
  <li class="list-inline-item">Item 3</li>
</ul>
```

<a href="#indice-menu">Voltar ao índice</a>

<h2 id="cores-background" align="center">Cores & Backgrounds</h2>

<h4 id="tag19">1. Classes para formatação de texto</h4>

`class="text-primary"`<br>

`class="text-secondary"`<br>

`class="text-success"`<br>

`class="text-info"`<br>

`class="text-warning"`<br>

`class="text-danger"`<br>

`class="text-light"`<br>

`class="text-dark"`<br>

`class="text-white"`<br>

`class="text-black-50"` - aplicada opacidade de 50% sobre a cor padrão;<br>

`class="text-white-50"` - recebe opacidade sobre a cor branca. Pode ser usado para formatar textos que ficam sobre imagens.

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag20">2. Formatação de links</h4>

- São utilizadas as mesmas classes da formatação de texto.

_Exemplo_

```html
<a href="#" class="text-primary">Link primary</a><br />

<a href="#" class="text-secondary">Link secondary</a><br />

<a href="#" class="text-success">Link success</a><br />
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag21">3. Backgrounds</h4>

- Ao invés de `text`, utiliza-se `bg` nas mesmas classes anteriores.

_Exemplo_

`class="bg-primary"`<br>

`class="bg-secondary"`<br>

`class="bg-success"`<br>

`class="bg-info"`<br>

`class="bg-warning"`<br>

`class="bg-danger"`<br>

`class="bg-light"`<br>

`class="bg-dark"`<br>

`class="bg-white"`<br>

`class="bg-transparent"`

<a href="#indice-menu">Voltar ao índice</a>

<h2 id="margin-padding" align="center">Margin & Padding</h2>

<h4 id="tag22">1. Margin</h4>

- O valor pode ser definido de 0 a 5, sendo uma unidade de medida do CSS (REM).
- As abreviações para aplicação são:

  - mt -> Margin Top
  - mb -> Margin Bottom
  - ml -> Margin Left
  - mr -> Margin Right
  - mx -> Margin no eixo x (horizontal) esquerda/direita
  - my -> Margin no eixo y (vertical) top/bottom
  - m -> Margin em todos os lados

_Exemplo_

```html
<p class="mt-5">Conteúdo</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag23">2. Padding</h4>

- A aplicação é igual ao margin, apenas trocando a letra "m" pela letra "p".

  - pt -> Padding Top
  - pb -> Padding Bottom
  - pl -> Padding Left
  - pr -> Padding Right
  - px -> Padding no eixo x (horizontal) esquerda/direita
  - py -> Padding no eixo y (vertical) top/bottom
  - p -> Padding em todos os lados

_Exemplo_

```html
<p class="pb-5">Conteúdo</p>
```

<a href="#indice-menu">Voltar ao índice</a>

<h2 id="tamanhos-bordas" align="center">Tamanhos e bordas</h2>

<h4 id="tag24">1. Classes de largura </h4>

- É possível utilizar classes para definir larguras por porcentagens no bootstrap.
- Utilizar: `w-%`, onde `w= width` e a `% será definida conforme desejar`.

_Exemplo_

```html
<div class="w-25">width 25%</div>

<div class="w-50">width 50%</div>

<div class="w-75">width 75%</div>

<div class="w-100">width 100%</div>

<div class="w-auto">width auto</div>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag25">2. Classes de altura </h4>

- É possível também utilizar classes para definir altura por porcentagens no bootstrap.
- Utilizar: `h-%`, onde `h= height` e a `% será definida conforme desejar`.

_Exemplo_

```html
<div class="h-25">height 25%</div>

<div class="h-50">height 50%</div>

<div class="h-75">height 75%</div>

<div class="h-100">height 100%</div>

<div class="h-auto">height auto</div>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag26">3. Bordas </h4>

- É possível aplicação de borda através de uma classe com o bootstrap.

_Atributos:_

border: todas as bordas<br>
border-top: borda superior<br>
border-bottom: borda inferior<br>
border-right: bordar direita<br>
border-left: borda esquerda<br>

Existe a possibilidade de aplicar cores nas bordas:
`primary, secondary, success, info, warning, danger, light, dark, white`

_Exemplos_

```html
<div class="border border-dark">todas as bordas</div>

<div class="border-top border-secondary">borda superior</div>

<div class="border-bottom border-danger">borda inferior</div>

<div class="border-right border-success">borda direita</div>

<div class="border-left border-info">borda esquerda</div>
```

<a href="#indice-menu">Voltar ao índice</a>

<h4 id="tag27">4. Border radius </h4>

- Existe a aplicação do border radius através de classes.

_Atributos_

rounded - arredonda todos os lados;
rounded-top - arredonda o topo;
rounded-right - arredonda a direita;
rounded-left - arredonda a esquerda;
rounded-circle - converte em um círculo.

_Exemplos_

```html
<div class="border rounded">rounded</div>

<div class="border rounded-top">rounded top</div>

<div class="border rounded-bottom">rounded bottom</div>

<div class="border rounded-right">rounded right</div>

<div class="border rounded-left">rounded left</div>

<div class="bg-light mb-2 p-5 border w-25 rounded-circle">rounded circle</div>
```

<a href="#indice-menu">Voltar ao índice</a>
