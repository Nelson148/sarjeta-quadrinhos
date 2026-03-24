🦸‍♂️ Sarjeta dos Quadrinhos

Um projeto de página web estática para um blog de quadrinhos, desenvolvido com HTML, Tailwind CSS e JavaScript, com foco em um visual estilizado e interativo.

📌 Descrição

O Sarjeta dos Quadrinhos é uma página que apresenta conteúdos sobre HQs, destacando:

Quadrinhos icônicos
Sessão de mais vistos (com carrossel)
Interface estilizada com tema artístico
Formulário de contato simples

O projeto utiliza Tailwind CSS para estilização rápida e responsiva, além de JavaScript para interatividade.

🚀 Tecnologias utilizadas
HTML5
Tailwind CSS (via CDN)
JavaScript (puro)
Google Fonts (Permanent Marker)
🎨 Funcionalidades
✅ Navbar
Links de navegação: Início, Sobre, Contato
Estilo com fonte personalizada
✅ Destaques principais
Exibição de capas de quadrinhos famosos
Layout responsivo com grid flexível
✅ Carrossel ("Mais vistos")
Navegação com botões:
⬅️ Anterior
➡️ Próximo
Animação suave com translateX
✅ Formulário
Campos:
Nome
Email
Botão de envio estilizado
⚠️ Observação
O formulário não possui backend (envio não funcional)
Script de modal está incluído, mas não há modal implementado no HTML
📂 Estrutura do projeto
📁 projeto
│
├── index.html
├── css/
│   └── styles.css
▶️ Como executar
Baixe ou clone o repositório
Abra o arquivo index.html no navegador
git clone <seu-repositorio>
cd projeto

Ou simplesmente dê dois cliques no arquivo HTML.

🧠 Lógica do Carrossel

O carrossel funciona com base em:

Controle de índice (index)
Manipulação de transform: translateX
Eventos de clique nos botões
images.style.transform = `translateX(-${index * 100}%)`;
