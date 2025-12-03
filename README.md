<div align="center">
	<h1>R2-D2 Profile – Tecnologias Web</h1>
	<p>Site estático demonstrando habilidades de HTML/CSS, semântica e acessibilidade.</p>
	<img src="./assets/images/beep-boop.png" alt="R2-D2" width="180" />
</div>

## 📌 Visão Geral
Este projeto é um site estático sobre o droide R2-D2, organizado em múltiplas páginas temáticas: Sobre, Aparições, Relacionamentos e Habilidades. Foi desenvolvido para praticar:
- Estruturação semântica (uso de `<main>`, `<section>`, `<header>`, `<nav>`)
- Componentização via classes CSS reutilizáveis
- Layout responsivo simples (menu hamburguer com checkbox)
- Boas práticas de acessibilidade (texto alternativo, hierarquia de headings)

## 🗂 Estrutura de Pastas
```
index.html
index.css
main.css
assets/
	images/
	gifs/
	video/
pages/
	about/
		about.html
		about.css
	appearances/
		appearances.html
		appearances.css
	relationships/
		relationships.html
		relationships.css
	skills/
		skills.html
		skills.css
```

## ✨ Principais Funcionalidades
- Navegação responsiva com menu hamburguer
- Página inicial com seção hero destacando o personagem
- Página "About" com vídeo em autoplay (muted + loop) e descrição
- Página "Appearances" com cards categorizados (filmes, séries, jogos)
- Página "Relationships" com grid de relações principais
- Página "Skills" (habilidades técnicas e funcionais do droide)
- Cards com imagens estáticas e GIFs para efeito visual

## ♿ Acessibilidade & Semântica
- Inclusão de `<main>` em todas as páginas para marcar conteúdo principal
- Uso consistente de `<nav>` para navegação global
- Headings hierárquicos (`h1` principal por página, subtítulos com `h2`/`h3`)
- `alt` em imagens relevantes (GIFs decorativos podem ter `aria-hidden="true"`)
- Vídeo configurado como `muted` + `autoplay` para evitar bloqueio do navegador

## 🧪 Tecnologias Utilizadas
- HTML5 semântico
- CSS3 (layout, tipografia, grid/flex)
- Mídias estáticas (PNG/JPG/GIF) e vídeo MP4

## 🚀 Como Executar Localmente
Clone o repositório e abra `index.html` diretamente no navegador ou use um servidor simples para melhor experiência.

### Opção 1: Abrir diretamente
1. Faça o download/clonagem.
2. Dê duplo clique em `index.html`.

### Opção 2: Extensão Live Server (VS Code)
1. Instale Live Server.
2. Clique em "Go Live" e navegue até a página inicial.

## 🔧 Padrões & Estilo
- `main.css`: estilos globais/resets/componentes compartilhados
- CSS específico por página para facilitar manutenção
- Classes utilitárias agrupam comportamentos visuais (ex.: `appearance-card`, `page-card`)
