### Aula 1

- [Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP)
- [Instar o Node.js](https://nodejs.org/pt)

**Adicionar Favicon**

```
Adicione o favicon.svg como icone da página.
```

**Extrair as variáveis CSS de cores da imagem.**

```
Transcreva a imagem como variáveis CSS mantendo o mesmo nome da imagem para cada token de cor.
```

**Utilizando Fonte do Google**

```
Importe a fonte Inter do Google Fonts com pesos 400, 500, 600 e 700 no index.html e aplique no styles.css a fonte nos elementos body, input e button.
```

**Criando o HTML da área de conteúdo**

```
Utilize o #Figma MCP e selecione está parte do Figma:

[LINK DA SELEÇÃO MAIN DO FIGMA]

Escreva dentro da #sym:main.main o HTML exatamante como está no Figma.

Se fizer sentido aplicar classe, utilize exatamente os nomes definidos no Figma. Preserve a ordem e hierarquia dos elementos e não invente atributos. Para icones busque na pasta #file:assets.

Também utilize o conteúdo do prompt-title e o prompt-content  que está no Figma.
```

[Guia de Solução de Problemas — MCP do Figma no VS Code](https://www.notion.so/Guia-de-Solu-o-de-Problemas-MCP-do-Figma-no-VS-Code-286395da577080fb84e0daea17e2863e?pvs=21)

**Implementando a estilização do main com IA**

```
Implemente o CSS para a classe main e de todos os elementos dentro do main respeitando o visual do Figma:

[LINK DA SELEÇÃO MAIN DO FIGMA]
```

---

### Aula 2

**Gerar o código do Placeholder do título e conteúdo**

```
Crie um objeto chamado elements que selecione por id os elementos prompt-title, prompt-content, title-wrapper e content-wrapper.

Implemente uma função updateEditableWrapperState(element, wrapper) que verifique se o elemento de texto possui conteúdo, se não houver adicione a classe is-empty.

Crie a função updateAllEditableStates() para atualizar o estado de todos os elementos, e configure ouvintes de evento input para o prompt-title e prompt-content para dentro de uma função chamada attachAllEditableHandlers atualizar seus respectivos wrappers em tempo real.

Por fim, implemente uma função init() que chame attachAllEditableHandlers e execute a inicialização.
```

Implementar abertura e fechamento da sidebar

```
Implemente a abertura e o fechamento da aside utilizando o openBtn para abrir e o collapseBtn para fechar.
```

**Gerar o conteúdo da sidebar**

```
Reecrie o HTML e CSS do sidebar_content com o input de search com o icone svg de search do lado esquerdo, button de novo prompt abaixo do input e uma linha abaixo do botão com um border-bottom do próprio search-container. Faça exatamente igual está aqui:

[LINK DA SELEÇÃO DO SEARCH-CONTAINER DO FIGMA]
```

---

### Aula 3

**Criar o componente de prompt da lista**

```
Utilize o MCP do Figma para criar dentro da ul.prompt-list o HTML e CSS de apenas um elemento li para o prompt-item exatamente como está no Figma com title e description de um lado e img de #file:remove.svg do outro:

[LINK DA SELEÇÃO DE UM PROMPT-ITEM DO FIGMA]

Para a li do componente utilize a classe prompt-item, para o título prompt-item-title e para a descrição prompt-item-description.

Para o botão utilize a classe CSS existente btn-icon. E para a imagem de remover dentro do botão utilize a classe icon e icon-trash.
```
