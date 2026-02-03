# Página de Vídeos (Layout estilo YouTube)

Projeto de página estática inspirado no layout do YouTube, com **vídeo principal** à esquerda e uma coluna de **vídeos recomendados** à direita.  
O foco é praticar **HTML semântico**, **CSS Grid** e **Flexbox**, além de organização de código (reset + style).

---

## 🧩 Funcionalidades / Componentes

- ✅ Vídeo principal (thumbnail + título + visualizações + descrição)
- ✅ Lista de vídeos recomendados (thumbnail + infos)
- ✅ Layout em duas colunas com `grid-template-columns: 1fr 322px`
- ✅ Espaçamento entre recomendados com `gap` (sem sobrar espaço no último item)
- ✅ Reset CSS básico (`box-sizing`, remover margens/paddings, remover bullets)

---

## 🛠️ Tecnologias

- **HTML5**
- **CSS3**
  - Grid Layout
  - Flexbox
- **Google Fonts (Roboto 300 / 700)**

---

## 📁 Estrutura de Pastas (sugerida)

```bash
.
├── index.html
└── src
    └── css
        ├── reset.css
        └── style.css
```
▶️ Como executar
Baixe/clone o projeto

Abra o arquivo index.html no navegador

🧠 O que foi praticado
Diferença entre Grid (layout da página) e Flex (organização interna dos componentes)

Uso do gap em Flex/Grid para espaçamento consistente

Organização de estilos com reset.css + style.css

Boas práticas de estruturação e reaproveitamento de classes

📌 Próximos passos (ideias de evolução)
 Corrigir a semântica dos recomendados (evitar <ul> com filhos que não sejam <li>)

 Adicionar responsividade (ex: virar 1 coluna no mobile)

 Padronizar espaçamentos e line-height para leitura melhor

 Adicionar hover nos cards e cursor de link

 Substituir imagens por thumbnails reais (ou assets locais)

👤 GitHub - [@wellfefe](https://github.com/wellfefe)

Frontend Mentor - [@wellfefe](https://www.frontendmentor.io/profile/wellfefe)