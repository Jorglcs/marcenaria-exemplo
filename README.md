# Forma — Marcenaria sob medida

Home page institucional fictícia feita com **React 19, JavaScript e Vite 7**. Identidade em verde e tons naturais, galeria com filtros, apresentação do estúdio, serviços, processo, depoimento, FAQ e simulação de orçamento.

## Executar

Requer Node.js 20.19+ ou 22.12+.

```bash
npm ci
npm run dev
```

## Produção

```bash
npm run build
npm run preview
```

A pasta `dist/` contém o site estático pronto para hospedagem. O Vite usa caminhos relativos para permitir publicação também em subdiretórios. Não há servidor de aplicação, banco de dados ou variáveis de ambiente.

## Personalizar

- `src/main.jsx`: textos, projetos, serviços, preços e formulário.
- `src/style.css`: identidade visual, responsividade e animações.
- `public/images/`: fotografias locais, sem dependência de URLs remotas em tempo de execução.
- `public/favicon.svg` e `index.html`: ícone, título e descrição.

Inclui menu mobile, links por âncoras, filtros de projetos, FAQ expansível, animações com IntersectionObserver, estados de foco, link de pular conteúdo e suporte a `prefers-reduced-motion`.

O formulário valida os campos e exibe confirmação de **simulação**. Não envia, armazena ou agenda nada. Para um projeto real, integrar um serviço de contato e adequar os textos antes da publicação. Marcas, depoimentos, projetos, números, endereços e valores são fictícios.

## Imagens e fontes

Fotografias ilustrativas do [Unsplash](https://unsplash.com/license), salvas em `public/images/`:

- Hero e sala: `photo-1600210492486-724fe5c67fb0`.
- Ambiente de trabalho: `photo-1449247709967-d4461a6a6103`.
- Cozinha: `photo-1556912172-45b7abe8b7e1`.
- Quarto: `photo-1611892440504-42a792e24d32`.

Fontes DM Sans e Manrope carregadas pelo Google Fonts, com fontes de sistema como alternativa. As imagens são referências visuais, não fotografias de projetos reais da marca fictícia.
