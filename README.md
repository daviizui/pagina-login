# pagina-login
Projeto de uma página de login usando HTML e CSS

## HTML

### Tags Semânticas

* **`<!DOCTYPE html>`**: Declara o tipo de documento como HTML5, garantindo que o navegador interprete o código corretamente.
* **`<html lang="en">`**: Define a raiz do documento HTML e especifica o idioma como inglês.
* **`<head>`**: Contém metadados sobre o documento, como o conjunto de caracteres, a viewport e o título da página.
* **`<meta charset="UTF-8" />`**: Define a codificação de caracteres como UTF-8, suportando uma ampla gama de caracteres.
* **`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`**: Garante que a página seja renderizada corretamente em diferentes dispositivos, ajustando a escala e a largura.
* **`<title>`**: Define o título da página, que é exibido na barra de título do navegador.
* **`<link>`**: Usado para vincular recursos externos, como folhas de estilo CSS e fontes.
* **`<body>`**: Contém o conteúdo principal da página.
* **`<form>`**: Representa um formulário HTML, usado para coletar dados do usuário.
* **`<input>`**: Cria campos de entrada para o usuário inserir dados, como nome de usuário e senha.
* **`<label>`**: Associa um texto a um controle de formulário, melhorando a acessibilidade.
* **`<button>`**: Cria um botão clicável, usado para enviar o formulário.
* **`<a>`**: Cria um link para outra página ou recurso.
* **`<p>`**: Representa um parágrafo de texto.
* **`<div>`**: Usado como um contêiner genérico para agrupar elementos HTML. Embora seja um elemento genérico, ele é vital para a estrutura do layout.

### Estrutura e Semântica

O código HTML está estruturado de forma clara e lógica, usando divs para agrupar elementos relacionados. O formulário é definido, com rótulos e campos de entrada. A utilização de tags como form, input, label e button, são de grande importância para a semantica do documento.

## CSS

### `display: flex`

* O CSS utiliza `display: flex` no `body` e no `.remember-forgot` para criar layouts flexíveis.
    * No `body`, `display: flex` centraliza o formulário na tela usando `justify-content: center` e `align-items: center`.
    * No `.remember-forgot`, `display: flex` organiza o checkbox e o link "Forgot password?" lado a lado, com espaçamento entre eles (`justify-content: space-between`).

### `position`

* O CSS usa `position: relative` no `.input-box` para posicionar o ícone dentro do campo de entrada.
* `position: absolute` é utilizado no `input-box i` para posicionar os icones dentro dos input.
* `transform: translateY(-50%)` é usado para centralizar verticalmente os ícones dentro dos campos de entrada.

### Pseudo-classes

* `input-box input::placeholder`: Estiliza o texto de espaço reservado nos campos de entrada.
* `remember-forgot a:hover` e `register-link p a:hover`: Estiliza o estado de foco dos links, adicionando um sublinhado quando o mouse passa por cima.

### Outros Atributos CSS Relevantes

* `background`: Usado para definir a imagem de fundo e as cores do formulário e do corpo.
* `border` e `border-radius`: Usados para estilizar as bordas e cantos do formulário e dos campos de entrada.
* `box-shadow`: Adiciona sombras aos elementos, criando um efeito visual.
* `padding` e `margin`: Controlam o espaçamento interno e externo dos elementos.
* `font-family`, `font-size` e `color`: Estilizam o texto.
* `outline: none`: Remove a borda de foco padrão dos campos de entrada e botões.
* `backdrop-filter: blur(20px)`: Aplica um efeito de desfoque ao fundo do formulário.
* `accent-color: #fff`: Estiliza a cor do checkbox.

### Fontes

* A fonte "Poppins" é importada do Google Fonts para estilizar o texto.

### Estilização Geral

O CSS utiliza seletores apropriados para estilizar os elementos. O uso de variáveis CSS e a estilização consistente contribuem para a legibilidade e manutenção do código.
