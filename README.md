# Sprint 1 Frontend - JOVI Camera Layout

## Sobre o Projeto

Layout interativo da câmera do smartphone JOVI desenvolvido como projeto acadêmico. Interface moderna e responsiva utilizando HTML5, CSS3 e Flexbox.

**Status:** ✅ Completo  
**Tipo:** Projeto Acadêmico (FIAP)  
**Foco:** Frontend Development

---

## Objetivos

- Desenvolver interface visual de câmera smartphone
- Aplicar conceitos de HTML/CSS estruturado
- Praticar layouts com Flexbox
- Criar responsividade e usabilidade

---

## Tecnologias Utilizadas

| Tecnologia | Descrição |
|-----------|-----------|
| **HTML5** | Estrutura semântica e acessibilidade |
| **CSS3** | Estilização e animações |
| **Flexbox** | Layout responsivo e flexível |

---

## 📁 Estrutura do Projeto

```
sprint1-frontend/
├── index.html          # Página principal
├── style.css          # Estilos gerais
├── flex.css           # Estilos Flexbox
└── README.md          # Documentação
```

### Descrição dos Arquivos

- **index.html**: Estrutura HTML com componentes da interface da câmera
- **style.css**: Estilização base, cores, tipografia e efeitos visuais
- **flex.css**: Layout responsivo com Flexbox, grid de controles

---

## Características

 **Interface Intuitiva**
- Controles principais bem organizados
- Botões de ação destacados
- Feedback visual ao interagir

 **Layout Responsivo**
- Adapta-se a diferentes tamanhos de tela
- Flexbox para distribuição de elementos
- Proporções mantidas em mobile e desktop

 **Design Moderno**
- Paleta de cores coerente
- Tipografia legível
- Espaçamento consistente

---

## Como Usar

### 1. Clonar o Repositório

```bash
git clone https://github.com/diogo-bittar/sprint1-frontend.git
cd sprint1-frontend
```

### 2. Abrir o Projeto

Abra o arquivo `index.html` no navegador:
- Duplo clique no arquivo
- Ou use um servidor local (recomendado):

```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com VS Code Live Server
# Extensão: Live Server
```

### 3. Acessar no Navegador

```
http://localhost:8000
```

---

## Componentes Principais

### Header
- Logo/título
- Informações de status

### Viewport da Câmera
- Área principal de visualização
- Indicadores de modo

### Controles
- Botão de captura (shutter)
- Seletor de modo (foto/vídeo)
- Ajustes rápidos

### Footer
- Ícones de ação
- Galeria rápida
- Configurações

---

## Conceitos Aprendidos

✅ Estrutura HTML semântica  
✅ CSS modularizado (style.css + flex.css)  
✅ Flexbox para layouts responsivos  
✅ Propriedades CSS avançadas  
✅ Organização de código  
✅ Responsividade mobile-first  

---

## Personalização

### Alterar Cores

Edite as variáveis em `style.css`:

```css
:root {
    --cor-primaria: #seu-valor;
    --cor-secundaria: #seu-valor;
    --cor-fundo: #seu-valor;
}
```

### Ajustar Layouts

Modifique as propriedades Flexbox em `flex.css`:

```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
}
```

---

## Responsividade

Testes realizados em:
-  Desktop (1920px - 1024px)
-  Tablet (768px - 480px)
-  Mobile (320px - 479px)

---

## Recursos Úteis

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [CSS Tricks - Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

---

## Licença

Este projeto é de código aberto para fins educacionais.

---

## Agradecimentos

- FIAP (Faculdade de Informática e Administração Paulista)
- Instrutores e colegas que contribuíram com feedback

---

**Última atualização:** Junho 2026  
**Versão:** 1.0.0
