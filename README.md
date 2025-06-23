# 🎨 Agência Design Digital -M

Este projeto é um site fictício de uma agência de branding e design digital, desenvolvido como **primeira prática com React**. Ele simula uma landing page institucional com foco em visual moderno, alternância de tema (claro/escuro) e responsividade.

## 📸 Visão Geral

- Página principal com banner informativo
- Sessão de experiências profissionais simuladas
- Rodapé com redes sociais e logomarca
- Alternância de tema claro/escuro
- Totalmente responsivo

---

## 🧪 Tecnologias Utilizadas

- **React** (via Next.js App Router)
- **CSS Modules** para estilização isolada
- **Next.js** para roteamento e estrutura do projeto
- **Google Fonts (Poppins)**
- **Imagens e ícones com Next/Image**

---

## 🚀 Como rodar o projeto localmente

### Pré-requisitos

- Node.js instalado
- npm ou yarn

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/RoberthVieira/Agencia-design-digital-M.git
2. Acesse a pasta do projeto:
   ```bash
   cd Agencia-design-digital-M
3. Instale as dependências:
   ```bash
   npm install
4. Rode o servidor de desenvolvimento:
   ```bash
   npm run dev
5. Acesse no navegador:
   ```
   http://localhost:3000

## 📂 Estrutura do Projeto
```
📁 app
 ┣ 📁 components
 ┃ ┣ Topo.jsx
 ┃ ┣ Banner.jsx
 ┃ ┣ SecaoExpTrabalho.jsx
 ┃ ┣ Card.jsx
 ┃ ┗ Rodape.jsx
 ┣ 📁 styles (via CSS Modules)
 ┣ page.jsx
 ┗ layout.jsx
```

## 💡 Aprendizados
Este projeto foi desenvolvido com o objetivo de:
Aprender os conceitos básicos de componentes React
Praticar a estilização com CSS Modules
Trabalhar com estados e props (useState, props.ehTemaEscuro)
Simular uma interface profissional com tema escuro e claro

## 📱 Responsividade
O projeto utiliza media queries para adaptar a interface a diferentes tamanhos de tela, ocultando a imagem do banner em dispositivos móveis e otimizando a leitura e usabilidade.

## 📝 Melhorias Futuras
Adicionar rotas para outras seções da agência
Incluir formulário de contato funcional
Publicar a aplicação via Vercel ou Netlify
Refatorar para uso de contexto global de tema

## Demo
https://roberthvieira.github.io/Agencia-design-digital-M/
