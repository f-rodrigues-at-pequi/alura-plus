HTML & CSS ALURA<a name="TOP"></a>
===================
- - - - 

### Aula 1 ###    

  Aprendizado  | Novidade? | Aprendi?
------------- | ------------- | -------------
Criar a pasta do projeto e os arquivos HTML e CSS no seu computador, assim como abrir a pasta no editor de código; | Não | Sim
Escrever o código base do arquivo HTML, através das tags que compõem a estrutura básica desse tipo de arquivo; | Não | Sim
Preencher os dados que são inseridos dentro da tag <head> que auxiliam o navegador a entender a codificação de caracteres, o tamanho do dispositivo e a conexão de arquivos externos; | Sim | Revisar
Estabelecer variáveis CSS e usar as mesmas, que ajudam a compreender melhor as cores por possuírem agora um nome ao invés do código hexadecimal; | Sim | Sim
Instalar a extensão Live Server para conseguir ver as alterações no código automaticamente ao salvar o arquivo; | Não | Sim
Alterar a cor de fundo da página com background-color e da escrita com color; | Sim | Sim
Inserir imagem de fundo com background-image e com a tag <img> assim como compreender suas diferenças de utilização. | Não | Sim

## Insights
  - Variáveis CSS auxiliam no entendimento do uso das cores por terem nomes que fazem sentido com o seu uso, consequentemente isso também facilita a atribuição nos elementos HTML. Além desses dois benefícios, 
  facilita na manutenção do código: é possível alterar o valor de alguma cor reescrevendo um único lugar do código.
  - Quando estamos inserindo uma imagem, é importante pensar: essa imagem faz parte do conteúdo da página?
    Se não, é possível colocá-la como background-image() de algum elemento.
  
- - - -

### Aula 2 ###    

| Aprendizado | Novidade? | Aprendi? |
|-------------|-----------|----------|
| Criar botões na página e como escolher qual elemento para isso; | Não | Sim |
| Como nomear classes com o padrão BEM (block element modifier); | Não | Sim |
| A diferença entre `<button>` e `<a>`; | Não | Sim |
| Unidade de medida responsiva `em`; | Não | Sim |
| `Display` inline e block; | Não | Revisar |
| Usar as propriedades CSS `grid` e `grid-template-columns` para dividir a tela; | Não | Revisar |
| Conferir através da ferramenta do desenvolvedor no navegador (F12) os grids na tela; | Sim | Sim |
| Detectar diferentes tipos de fontes e tamanhos de letras no Figma; | Sim | Sim |
| Escolher fontes no fonts.google.com; | Sim | Sim |
| Importar fontes externas no arquivo HTML; | Sim | Sim |
| Usar variáveis CSS para armazenar valores além de cores como o nome da fonte; | Não | Sim |
| Aplicar a fonte importada nos elementos através do CSS e outros atributos relacionados: `font-family`, `font-size`, `font-weight`; | Não | Revisar |
| Remover a decoração do texto de links através do `text-decoration`; | Não | Sim |

## Insights
  - `display: grid;
grid-template-columns: 50% 25% 25%;` Dessa maneira, a primeira coluna ocupará metade da tela e em seguida serão construídas duas colunas menores,
que ocupam a metade do tamanho da primeira cada uma.
  - Quando queremos que um evento aconteça a partir do clique do mouse, utilizamos os botões.

- - - -

### Aula 3 ###    

| Aprendizado | Novidade? | Aprendi? |
|-------------|-----------|----------|
| Afastar elementos dos cantos da tela e de outros elementos; | Sim | Sim |
| A diferença entre `margin` e `padding`; | Não | Revisar |
| Diversas maneiras de determinar os valores e as direções das margens dentro da propriedade `margin`; | Sim | Sim |
| Construir uma nova `section`; | Não | Sim |
| Reutilizar estilos através das classes dentro da nova `section`; | Sim | Sim |
| Atribuir mais de uma classe nos elementos para incluir novas estilizações além das existentes; | Sim | Sim |

## Insights
  - Margins realmente criam espaço ao redor do elemento e paddings criam dentro dele, ou seja, o padding afasta o
  conteúdo da borda e não um elemento do outro. Por fim, também 
  podemos configurar valores diferentes para cada lado do elemento e, no vídeo, vimos diversas maneiras de fazer isso.
  - ```html
    <div class="container">
    <h2 class="container__titulo">Alura Cats!</h2>
    <img src="https://thecatapi.com/api/images/get?format=src&type=gif" alt=”imagem de gatos” class="container__imagem">
      <p>Para mais informações:</p>
    <a href="www.alura.com.br" class="container__botao">Acesse a Alura<a>
    </div>
    ```
O código começa com um elemento de bloco (a div), ou seja, que tem display block, e 
há elementos dentro dele que são inline. Dessa maneira, usar a propriedade text-align na div permitirá alinhar 
para qualquer lado que você desejar os elementos filhos da div.

- - - -

### Aula 4 ###    

| Aprendizado | Novidade? | Aprendi? |
|-------------|-----------|----------|
| Usar flexbox e seu significado; | NãO | Revisar |
| Flex-containers, flex-itens, flex-direction; | Não | Revisar |
| A tag `footer`; | Sim | Sim |
| Colocar o conhecimento em prática; | Sim | Sim |
| Pseudo-classes no CSS: `hover` e `active`; | Sim | Sim |
- - - -

### Aula 5 ###    

| Aprendizado | Novidade? | Aprendi? |
|-------------|-----------|----------|
| Criar uma conta no Github; | Não | Sim |
| Construir um repositório com o código do curso; | Não | Sim |
| Escrever commits; | Não | Sim |
| Fazer deploy no Github Pages e Vercel; | Sim | Sim |
| Editar código no VSCode Web; | Sim | Sim |
| Enviar alterações para o repositório já existente; | Não | Sim |
