# Projeto: Local Turístico - Conheça Busan

Este projeto apresenta uma página HTML sobre Busan, uma cidade turística na Coreia do Sul. A estrutura HTML e o estilo CSS criam uma interface informativa e agradável para os visitantes que desejam aprender mais sobre esse destino.

---

## Estrutura HTML

### Elementos Básicos

- `<!DOCTYPE html>`: Define o tipo de documento como HTML5.
- `<html lang="pt-br">`: Indica o idioma principal do conteúdo, facilitando o entendimento para navegadores e motores de busca.
- `<head>`: Contém metadados e links importantes, como fontes e CSS.
- `<meta charset="UTF-8">`: Define a codificação de caracteres para UTF-8, garantindo a exibição correta de caracteres especiais.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ajusta a escala e a visualização para dispositivos móveis.

### Links e Fontes

- `<link rel="preconnect">`: Otimiza o carregamento de fontes externas (Google Fonts) ao estabelecer uma conexão prévia.
- `<link rel="stylesheet" href="styles.css">`: Vincula o arquivo CSS para estilização.
- `<link href="https://fonts.googleapis.com/css2?...">`: Importa as fontes "Alice" e "Open Sans" para estilização personalizada.

### Estrutura do Conteúdo

- `<main>`: Bloco principal da página que contém a maioria do conteúdo.
- `<div class="title-page">`: Agrupa o título principal e subtítulo da página.
- `<div class="description-image">`: Contém uma imagem e uma breve descrição de Busan.
- `<div class="content-list">`: Apresenta uma lista de locais turísticos, com imagens e descrições.

### Listas e Cartões

- `<ol class="custom-list">`: Uma lista ordenada personalizada que exibe cartões de locais turísticos.
- `<li>`: Cada item de lista é utilizado para um destino específico em Busan.
- `<div class="card-travel">`: Estrutura de cada cartão, contendo uma imagem, título e descrição do local.

### Rodapé

- `<footer>`: Contém uma mensagem final personalizada e o nome do desenvolvedor, estilizado com um ícone de coração.

---

## Estilos CSS

### Resete Global

- `* { padding: 0; margin: 0; box-sizing: border-box; }`: Remove margens e espaçamentos padrão para um estilo consistente.
- `ul { list-style-type: none; }`: Remove o marcador de lista padrão.

### Layout Geral

- `body`: Define o layout com `inline-flex`, espaçamentos e alinhamentos personalizados.
- `main`: Configura o layout principal, com largura e organização em coluna.

### Elementos de Texto

- `.headline`: Estiliza títulos com a cor #E1624F, fonte "Open Sans", tamanho 16px e transforma o texto em maiúsculas.
- `.Conheca-Busan`: Define o estilo do título principal, com tamanho de 36px e fonte "Open Sans".

### Imagens

- `.description-image img` e `.card-travel img`: Aplica bordas arredondadas para um estilo mais suave.

### Divisores e Bordas

- `.divisor`: Cria uma linha horizontal para separar seções, com largura de 1120px e altura de 1px.

### Listas e Cartões

- `.content-list`: Exibe a lista em coluna, com espaçamento entre os itens.
- `.custom-list`: Remove margens e ajusta a indentação para uma lista personalizada.
- `.card-travel`: Organiza os cartões em coluna, ajustando o espaçamento interno.

### Rodapé

- `.FeitoCom`, `.PorDnlDev`: Estilizam os textos com espaçamentos para melhor legibilidade.

---

## Fontes e Cores

- Fontes: Utiliza "Open Sans" para textos principais e "Alice" para o rodapé.
- Cores: Tons de cinza (#333) e destaque vermelho (#E1624F) para criar contraste e hierarquia visual.

---
