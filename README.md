# Adriano Gomes de Deus Advocacia

Landing page institucional estática para o escritório Adriano Gomes de Deus Advocacia, com foco em apresentação profissional, áreas de atuação e geração de contato via WhatsApp.

Site publicado em:
`https://linksites.github.io/gomes-de-deus/`

## Estrutura

```text
.
|-- index.html
|-- css/
|   `-- styles.css
`-- assets/
    |-- favicon.png
    |-- fotoperfil.jpeg
    |-- fotoperfil-perfil.jpeg
    |-- logo.jpg
    |-- logogd.jpeg
    `-- imagens-enderecos.json
```

## Tecnologias

- HTML5
- CSS3
- JavaScript vanilla
- Google Maps Embed
- WhatsApp deep link

## Funcionalidades atuais

- Hero institucional com CTA principal para contato
- Menu responsivo com versão mobile
- Alternância entre tema escuro e claro com persistência em `localStorage`
- Seções de perfil profissional, áreas de atuação, sobre e contato
- Formulário que abre mensagem pré-preenchida no WhatsApp
- Metadados básicos para SEO e compartilhamento social

## Como rodar localmente

Como o projeto é estático, basta servir a pasta por um servidor HTTP simples.

Com Python:

```bash
python -m http.server 4173
```

Depois abra:

```text
http://127.0.0.1:4173
```

## Edição rápida

- Conteúdo principal: [index.html](C:/Projeto/gomes-de-deus/index.html)
- Estilos globais e responsividade: [css/styles.css](C:/Projeto/gomes-de-deus/css/styles.css)
- Imagens e favicon: pasta [assets](C:/Projeto/gomes-de-deus/assets)

## Publicação

Hoje o projeto aponta para GitHub Pages. Se a URL final mudar, atualize estes pontos em [index.html](C:/Projeto/gomes-de-deus/index.html):

- `<link rel="canonical">`
- metas `og:*`
- campo `url` do JSON-LD
- campo `image` do JSON-LD, se a imagem pública mudar

## Auditoria técnica resumida

Itens revisados nesta etapa:

- semântica básica e landmarks principais
- comportamento do menu mobile
- fluxo do formulário para WhatsApp
- consistência visual da primeira dobra
- SEO básico e dados estruturados
- validação HTML

Melhorias aplicadas:

- remoção de `onsubmit` inline
- correção do link gerado para WhatsApp
- fechamento automático do menu ao redimensionar a tela
- bloqueio de rolagem quando o menu mobile está aberto
- remoção de estilos inline restantes
- adição de `skip link`, `focus-visible`, `canonical` e Open Graph

## Próximos passos

O plano detalhado de evolução está em [ROADMAP.md](C:/Projeto/gomes-de-deus/ROADMAP.md).
