# Página Pessoal / Currículo
Repositório com objetivo de mostrar a estrutura básica de uma página com **HTML** e **CSS**.

# Estrutura HTML da Página
O arquivo HTML é responsável pela estruturação do conteúdo da página pessoal. Abaixo, estão descritas as principais partes e componentes do código:

## 🔍 Estrutura Principal
- `<!DOCTYPE html>`: Define o tipo do documento como HTML5.

- `<html lang="pt">`: Inicia o documento HTML, indicando que o idioma principal é o português.

- `<head>`: Contém metadados sobre o documento:

  - `<meta charset="UTF-8">`: Define a codificação de caracteres para UTF-8, permitindo a exibição correta de acentos e símbolos.

  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Torna a página responsiva em dispositivos móveis.

  - `<title>`: Define o título da página que aparece na aba do navegador.

  - `<link rel="stylesheet" href="style.css">`: Importa o arquivo CSS externo chamado style.css para estilização.

## 📝 Estrutura do Corpo (Body)
A estrutura principal do conteúdo está dentro da tag `<body>`, organizada da seguinte forma:

✅ Cabeçalho e Navegação
- `<h1>Página Pessoal</h1>`: Título principal da página.

- `<hr>`: Linha horizontal para separação visual.

- `<div class="menu">`: Menu de navegação com links internos (âncoras) que levam para as seções da própria página utilizando IDs:

![{5B179F68-9F04-4E78-8316-420A1C73934B}](https://github.com/user-attachments/assets/ea3f8de6-b1e7-4354-a3aa-046e06fb4aad)

- `<a href="#sobreMim">`Sobre mim</a>: Leva até a seção "Sobre Mim".

- `<a href="#formacao">`Formação</a>: Leva até a seção "Formação".

- `<a href="#hobbies">Hobbies</a>`: Leva até a seção "Hobbies".

- `<a href="#redesSociais">Redes Sociais</a>`: Leva até a seção "Redes Sociais".

## 🖼️ Imagem de Perfil
- `<div class="imagemPerfil">`: Contém a imagem de perfil com a tag `<img>`. A URL da imagem é externa, apontando para o Pixabay(site onde contem a imagem).

- Outra opção é usar uma imagem já existente no seu computador, para isso basta substituir o link pela referência do arquivo local, como por exemplo:
    
    <img src="./imagens/perfil.jpg">

## 📌 Seções da Página
As seções estão identificadas com IDs para serem acessíveis pelos links do menu:

- `<section class="sobreMim">`: Informações pessoais.

- `<section class="formacao">`: Lista de formações e cursos.

- `<section class="hobbies">`: Lista dos hobbies.

- `<section class="redesSociais">`: Informações de contato e redes sociais.

## 📌 Lista Ordenada e Desordenada
Dentro das seções, foram usadas listas para organizar:

- `<ol>` no menu de navegação para os itens clicáveis.

- `<li>` nas seções de Formação e Hobbies.

## 📌 Links Externos e Contatos
- Os contatos são apresentados como links clicáveis para redes sociais (Instagram, Facebook) e informações de contato (WhatsApp e E-mail).

## 📌 Rodapé (Footer)
- `<footer>`: Inclui os direitos autorais e a menção da aula de HTML e CSS.

# Estilização CSS da Página
O arquivo CSS (style.css) é responsável por definir o estilo visual da página HTML, melhorando a apresentação e a organização dos elementos. Abaixo estão descritos alguns elementos que foram aplicados na página:

## 🎨 Aplicando cor do fundo a página
- Tag `body{}`

  - `background-color: rgb(43, 44, 82)`: Define a cor de fundo da página para um tom de azul escuro (rgb(43, 44, 82)).

## 🏷️ Cabeçalho e Títulos
- Tag: `h1{}`

    - `text-align: center;`- Centraliza o título principal da página.
  
    - `color: white;`- Define a cor do texto como branca.

    - `font-style: italic;`- Aplica estilo itálico para destacar o título.

- Tag `h2{}`:

    - `color: white;`: Define a cor dos subtítulos como branca para contraste com o fundo.

## 🖼️ Imagem de Perfil
- Classe: `.imagemPerfil`:
  
    - `text-align: center;` - Centraliza a imagem de perfil na tela.

- Tag: `img`:

    - `width: 50%;` - Define a largura e a altura da imagem como 50% do espaço disponível.

    - `height: 50%;` Aplica um efeito circular utilizando border-radius: 50%.
 
    -  `border-radius: 50%;` — Arredonda a imagem.
 
## 📌 Menu de Navegação
- Classe: `.menu{}`:

    - `display: flex;` — Organiza em linha.

    - `align-items: center;` — Centraliza verticalmente.

    - `justify-content: center;` — Centraliza horizontalmente.

    - `padding: 20px;` — Adiciona espaçamento.

- Tag: `ol{}`:

    - `text-align: center;` — Centraliza o texto.

    - `font-weight: bold;` — Negrito.

- Tag `a{}`:

    - `text-decoration: none;` — Remove sublinhado.

    - `color: white;` — Define a cor como branca.

    - `font-size: 18px;` — Define o tamanho.

- Classe: `.redesSociais a{}`:

    - `color: black;` — Links em preto.

## 📌 Seções da Página
As seções são estilizadas para melhorar a aparência visual e destacar as informações.

- Classes: `.sobreMim{}`, `.formacao{}`, `.hobbies{}`, `.redesSociais{}`:

    - `background-color`: rgb(214, 207, 243); — Cor de fundo lilás.

    - `color: black;` — Cor do texto preta.

    - `border-radius: 10px;` — Bordas arredondadas.

    - `padding: 10px;` — Adiciona espaçamento interno.

    - `font-size: 18px;` — Tamanho da fonte.

## 📌 Rodapé
- Tag: `footer`

    - `font-style: italic;` — Texto em itálico.

    - `font-weight: bold;` — Texto em negrito.

    - `color: rgb(43, 44, 82);` — Cor azul escuro.

    - `background-color: white;` — Fundo branco.

    - `text-align: center;` — Centraliza o texto.

    - `font-size: 15px;` — Define o tamanho da fonte.

### 📢 Propósito Educacional
  > Este projeto foi desenvolvido com o objetivo de ensinar alunos de uma escola sobre a criação de uma página web utilizando HTML e CSS, no contexto da atividade "Criando Minha Primeira Tela". A proposta foi apresentar, de forma prática e acessível, os conceitos fundamentais de estruturação e estilização de páginas web. <br>
Você pode acompanhar mais sobre o projeto através desta publicação no **[LinkedIn](https://www.linkedin.com/posts/dougolvr_ravy-cinthya-projetodeextensao-activity-7271975878358687744-39f8?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEIuvvgBtHmBJvP4CuyzKRNhPEVj1i2QygE).**

