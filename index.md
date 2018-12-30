
---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```


# 1º Post - Seja bem vindo

Pretendo postar tudo sobre o que eu tiver feito nos seguintes assuntos:

 - Yii Framework;
   - RBAC;
 - Firebase;
 - Github Pages;
 - Git;
 - Manjaro Linux;
   - Instalação LAMPP;  
 - Hadoop;
 - Wordpress;
   - PWA;
   - Plugins;
 - Métodos jQuery;
 - BeerJS;
 - ERP;
 - Arduino e boards que eu mexer;
 - Snappy;
 - Códigos postados no GitHub;
 - Boas práticas;
 - MS Visual Studio Code;
 - Realidade virtual(Com ou sem Software Livre);

# 2º Post - Git!

A minha ideia de falar sobre Git é para documentar os comandos que sei em um lugar além da minha memória. Git é um sistema de controle de versões(VCS) que está sendo muito utilizado, acredito que por existirem muitos gerenciadores de repositórios online, tais como: github, bitbucket, gitlab, etc... Pode acontecer de eu escrever "Why Git?" mais profundamente depois.
  Não vou falar sobre a instalação do git.
  Quando nos deparamos com o git instalado na máquina, temos duas possibilidades de ações que podem ser tomadas:
  1. Clonar um repositório(copiar os arquivos do repositório para nossa máquina);
  ```sh
  git clone https://github.com/irioborges/irioborges.git
  ```
  2. Criar um novo repositório. Ele será o origin. Posteriormente será enviado para o repositório master, é por isso do git ser distribuiído;
  ```sh
  git init
  ```

  3. Independente da ação escolhida, o próximo passo com certeza será a alteração ou criação de arquivos. Em ambos os casos estaremos localmente em um repositório origin, pois o master estará em algum gerenciador de repositório. Após criados/alterados arquivos neste repositório, podemos adicionar estas criações/alterações na head através do comando:
  ```sh
  git add * //para todos os arquivos criados/alterados
  ```
ou
```sh
git add nome_do_arquivo //para adicionar somente nome_do_arquivo na head
```

A Head é o local onde ficam os arquivos que irão ser acrescentados oficialmente no repositório(por enquanto no origin).

4. Agora é hora do commit. É o comando utilizado para confirmar as alterações e gravar elas no repositório.
```sh
git commit -m "First commit"
```
Cabe ressaltar que o parâmetro -m é obrigatório.
