# o-basico-do-html
Aqui você encontrará um suporte para aprender o básico de HTML
Estrutura de Pastas:

Blog-Simples-HTML-CSS/
├── styles.css          # Arquivo de estilos CSS**
├── images/             # Pasta para armazenar imagens
├── post.html           # Exemplo de página de postagem
└── README.md           # Instruções 
# Blog Simples com HTML e CSS

Este projeto é um exemplo básico de um blog estático criado com HTML e CSS. Ele foi desenvolvido para ajudar iniciantes a entender os conceitos fundamentais de estruturação de páginas web e estilização.

## Estrutura do Projeto

- **`index.html`**: Página inicial do blog(ignorar).
- **`styles.css`**: Arquivo de estilos para personalizar a aparência do blog.
- **`images/`**: Pasta para armazenar imagens usadas no blog.
- **`about.html`**: Página "Sobre" com informações sobre o blog(ignorar).
- **`post.html`**: Exemplo de uma página de postagem.

## Como Funciona?

### 1. HTML Básico
O HTML (HyperText Markup Language) é usado para estruturar o conteúdo da página. Aqui estão os principais elementos que usamos:

- **`<header>`**: Cabeçalho da página (título e menu).
- **`<main>`**: Conteúdo principal da página.
- **`<article>`**: Representa uma postagem do blog.
- **`<footer>`**: Rodapé da página.(colocar as referências)

Exemplo de código HTML:
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Meu Blog</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">Sobre</a>
        </nav>
    </header>
    <main>
        <article>
            <h2>Título da Postagem</h2>
            <p>Conteúdo da postagem...</p>
        </article>
    </main>
    <footer>
        <p>&copy; 2023 Meu Blog</p>
    </footer>
</body>
</html>´´´
