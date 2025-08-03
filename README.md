# 🎓 Minicurso: Introdução ao TailwindCSS: Construindo uma página web sem CSS

**Semana Acadêmica da Computação – SACOMP**

Bem-vindos ao repositório oficial do minicurso **"Introdução ao TailwindCSS: Construindo uma página web sem CSS"**. Aqui você encontrará os recursos necessários para acompanhar o conteúdo teórico e prático apresentado durante o evento.

---

## 📌 Sobre o Minicurso

Este minicurso tem como objetivo apresentar os conceitos fundamentais do framework **TailwindCSS** e demonstrar como construir interfaces web modernas e responsivas utilizando apenas classes utilitárias, sem a necessidade de escrever CSS manualmente.

Durante o encontro, desenvolveremos **uma landing page responsiva**, com base em um layout previamente construído no Figma.

---

## 🧰 Pré-requisitos

Para acompanhar a atividade prática, recomenda-se que você tenha instalado em sua máquina:

- Um editor de código (ex: [Visual Studio Code](https://code.visualstudio.com/))
- [Node.js](https://nodejs.org/en/) instalado
- Conhecimento básico de HTML

---

## 🎨 Layout de Referência
O layout que será reproduzido está disponível no Figma:

🔗 Acessar Layout no Figma: [Protótipo](https://encr.pw/prototipo) [Imagens](https://drive.google.com/drive/folders/1rbDEZguk8qCNbmZuhqzdueOdPrFnV6J4?usp=sharing)

---

## 💻 Instalação do TailwindCSS
Para instalar o TailwindCSS você precisa acessar a documentação do framework no link [TailwindCSS](https://tailwindcss.com/)
Após é só seguir os passos:
-  Via CLI: A maneira mais simples e rápida de começar a usar o Tailwind CSS do zero
-  1º passo: Abra a pasta do projeto no VScode. Abra o terminal e execute o seguinte comando para instalar o Tailwind via NPM:
- npm install tailwindcss @tailwindcss/cli 
-  2º passo: Importando o Tailwind ao nosso CSS
-  Crie a seguinte estrutura de pastas:
-  MINICURSO
│
├── src/

│   ├── index.html

│   └── input.css

-   Abra o arquivo input.css e cole o seguinte comando:
-   @import "tailwindcss"; 
- 3º passo: Executando o tailwind. Esse comando serve para scanear os nossos arquivos de origem em busca de classes para construir nosso CSS.
- No terminal execute o seguinte comando:
- npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
- 4º passo: Começando a usar:
- Adicione seu arquivo CSS compilado ao <head> e comece a usar as classes utilitárias do Tailwind para estilizar seu conteúdo.
- <link href=”./output.css" rel="stylesheet">

---

## 💬 Contato
Dúvidas, sugestões ou problemas? Entre em contato comigo:

👨‍🏫 Nome: Prof. Me. Bruna Ribeiro

📸 Instagram: [@brunabgribeiro](https://www.instagram.com/brunabgribeiro/)

📧 E-mail: brgribeiro@senacrs.com.br

💼 LinkedIn: [in/brunagoncalvesribeiro/](https://www.linkedin.com/in/brunagoncalvesribeiro/)

## 📚 Slides da Apresentação
Você pode revisar os slides utilizados no minicurso através do link abaixo:

📑 Ver Slides: [Introdução ao TailwindCSS](https://www.canva.com/design/DAGu-ax_3jo/nmnrPQ5TYGCqfkrzSsUJXg/view?utm_content=DAGu-ax_3jo&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h0b895a8093)

---
