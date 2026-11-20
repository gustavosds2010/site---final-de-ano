# 🍣 Tsuki Sushi

> *Tradição, sabor e arte em cada peça.*

Projeto final desenvolvido com o objetivo de criar uma aplicação web interativa e funcional para um restaurante japonês, aplicando conceitos modernos de desenvolvimento front-end, lógica com JavaScript e controle de versão com Git e GitHub.

---

## 🚀 Sobre o Projeto

O **Tsuki Sushi** evoluiu de uma página estática básica para uma aplicação web dinâmica e completa de e-commerce. O sistema simula a experiência real de um cliente navegando por um cardápio digital, explorando detalhes dos produtos, gerenciando um carrinho de compras interativo, alternando temas visuais e enviando mensagens validadas via formulário.

---

## ✨ Funcionalidades Implementadas

* **Catálogo Dinâmico:** Renderização de pratos tradicionais japoneses (Sushi, Nigiri, Temaki e Yakisoba) com preços, descrições detalhadas e imagens.
* **Carrinho de Compras Interativo:** 
  * Adição, controle de quantidade e remoção de itens.
  * Cálculo em tempo real do submetodo, quantidade de itens e valor total da compra.
  * Janela modal flutuante dedicada para visualização do carrinho.
* **Janela Modal de Detalhes:** Exibição de informações aprofundadas ao clicar no botão "Detalhes" de cada prato, com suporte a fechamento por clique externo ou pela tecla `Esc`.
* **Modo Claro / Escuro (Dark/Light Mode):** Alternância dinâmica de tema visual com salvamento automático da preferência do usuário utilizando o `localStorage`.
* **Validação Robusta de Formulário:** Validação de campos (como nome com mínimo de letras, e-mail e telefone) com feedback visual de erros/sucessos e navegação inteligente por scroll.
* **Design Responsivo:** Layout totalmente adaptado para diferentes dispositivos (smartphones, tablets e computadores) utilizando Flexbox e Media Queries.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e práticas:

* **HTML5:** Estruturação semântica e acessível da página (com uso de elementos de diálogo e formulários avançados).
* **CSS3:** Estilização visual customizada, variáveis de tema, efeitos de transição/hover e responsividade.
* **JavaScript (ES6+):** Manipulação do DOM, controle de estado, funções de manipulação de arrays (`map`, `filter`, `reduce`), eventos (`addEventListener`) e armazenamento local (`localStorage`).
* **Git & GitHub:** Controle de versionamento de código, histórico de commits e hospedagem do repositório.

---

## 📁 Estrutura de Arquivos

```text
Site Final de Ano/
│
├── imagens/              # Pasta contendo os recursos visuais e fundos do site
├── index.html            # Arquivo principal de marcação HTML
├── style.css             # Estilos visuais e regras de responsividade
├── script.js             # Lógica de interatividade, carrinho e validações
└── README.md             # Documentação oficial do projeto
```
## 🚀 Como Executar o Projeto Localmente
Clone este repositório para a sua máquina:

```
git clone [https://github.com/gustavosds2010/site---final-de-ano](https://github.com/gustavosds2010/site---final-de-ano)
```

Abra a pasta do projeto utilizando o Visual Studio Code.

Para a melhor experiência, utilize a extensão Live Server do VS Code:

Clique com o botão direito no arquivo index.html.

Selecione "Open with Live Server".

O projeto abrirá automaticamente no seu navegador padrão com atualização dinâmica.

## 👨‍💻 Autor
Projeto desenvolvido por Gustavo Soares como parte da entrega do projeto final do módulo 1 do curso.