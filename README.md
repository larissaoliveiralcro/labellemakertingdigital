 # 💄 La Belle — Marketing Digital

> Site acadêmico do projeto de Administração sobre como o Marketing Digital pode ajudar pequenos negócios a conquistar clientes, fortalecer a marca e aumentar seus resultados.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

---

## 📖 Sobre o projeto

Este site foi desenvolvido como **atividade acadêmica do curso de Administração** e apresenta uma pesquisa completa sobre os impactos da divulgação digital em pequenos negócios, tendo como estudo de caso a empresa fictícia **La Belle**, do ramo de roupas e acessórios.

A situação-problema que orienta o projeto é:

> *"Como a falta de divulgação afeta o reconhecimento da marca e as vendas da La Belle?"*

A partir de uma pesquisa de campo (entrevista com a proprietária, questionário online com 16 respostas e observação do perfil da empresa), o grupo estruturou uma **proposta administrativa de Marketing Digital de baixo custo** para reverter o cenário de perda de clientes.

---

## 🎯 Objetivos

- **Geral:** explicar como estratégias de Marketing Digital podem ajudar pequenos negócios a conquistar clientes e melhorar seus resultados.
- **Específicos:**
  - Compreender os conceitos de Marketing Digital e tráfego pago;
  - Investigar, por meio de pesquisa de campo, o impacto da divulgação nas vendas;
  - Analisar os dados coletados e identificar o problema central da La Belle;
  - Propor um plano de ação digital viável para a realidade do pequeno negócio.

---

## ✨ Funcionalidades

- 🎨 **Design responsivo** com identidade visual sofisticada (paleta vinho, dourado e creme)
- 📱 **Menu mobile** com botão hambúrguer e destaque automático da seção ativa
- 📊 **Gráficos interativos** com Chart.js exibindo os dados reais da pesquisa
- 🎬 **Animações de scroll reveal** com IntersectionObserver
- 🔝 **Botão "voltar ao topo"** flutuante
- 🧭 **Rolagem suave** com compensação do menu fixo
- ♿ **Acessibilidade** com `aria-labels`, HTML semântico e contraste adequado

---

## 🗂️ Estrutura do site

| Seção | Conteúdo |
|-------|----------|
| 🏠 **Início** | Apresentação do projeto, integrantes, situação-problema e objetivo |
| 📚 **Tema** | Definições, importância do marketing, atividades e exemplos práticos |
| 🔍 **Pesquisa** | Metodologia, questionário, gráficos de resultados e respostas abertas |
| 📈 **Análise** | Interpretação dos dados e opinião fundamentada do grupo |
| 💡 **Solução** | Plano de Marketing Digital com 6 etapas de implementação |
| ✅ **Conclusão** | Reflexões individuais, diário de uso de IA e fontes |

---

## 📊 Principais resultados da pesquisa

| Indicador | Resultado |
|-----------|-----------|
| Conhecem novas empresas por meio de propagandas | **81,3%** |
| Acreditam que a falta de divulgação prejudica muito o crescimento | **81,3%** |
| Já deixaram de comprar por não conhecer a empresa | **62,5%** |
| Conhecem alguma empresa com pouca divulgação | **75%** |
| Valorizam redes sociais como principal meio | **62,5%** |
| Consideram panfletos importantes | **0%** |

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica
- **CSS3** — variáveis CSS, grid, flexbox, animações
- **JavaScript (Vanilla)** — interatividade, scroll spy, IntersectionObserver
- **[Chart.js 4.4.1](https://www.chartjs.org/)** — gráficos interativos (via CDN)
- **[Google Fonts](https://fonts.google.com/)** — Playfair Display e Poppins

> 💡 Não há dependências de build, frameworks ou `npm install`. Basta abrir o `index.html` no navegador.

---

## 🚀 Como executar localmente

### Opção 1 — Abrir direto no navegador


Opção 2 — Servidor local (recomendado)
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/la-belle-marketing.git

# Acesse a pasta
cd la-belle-marketing

# Abra o arquivo index.html no navegador

# Com Python 3
python -m http.server 8000

# Com Node.js (npx)
npx serve


📁 Estrutura do projeto
la-belle-marketing/
│
├── index.html       # Página principal (HTML + CSS + JS inline)
├── README.md        # Este arquivo
└── LICENSE          # Licença MIT (opcional)

O projeto foi construído como página única (single page), com CSS e JavaScript embutidos no index.html para facilitar o deploy em plataformas como GitHub Pages.

🌐 Deploy no GitHub Pages
Faça o push do projeto para um repositório no GitHub

Vá em Settings → Pages

Em Source, selecione Deploy from a branch

Escolha a branch main e a pasta / (root)

Clique em Save

Seu site estará disponível em:
https://seu-usuario.github.io/la-belle-marketing/

🤖 Sobre o uso de Inteligência Artificial
O projeto adota uma postura de transparência total quanto ao uso de IA. Todas as interações com ferramentas como Gemini e ChatGPT estão documentadas no site, na seção Diário de Utilização da IA, com:

📅 Data da interação

🛠️ Ferramenta utilizada

💬 O que foi solicitado

✅ Como a resposta foi aplicada

A IA foi utilizada como ferramenta de apoio à pesquisa, organização e programação — mas as decisões, a análise crítica e a adaptação do conteúdo foram feitas pelo grupo.

👩‍🎓 Autoras
<table> <tr> <td align="center"> <b>Larissa Cabral de Oliveira</b><br> <sub>Pesquisa e análise de dados</sub> </td> <td align="center"> <b>Livia Tayná Ferreira da Silva</b><br> <sub>Pesquisa e redação</sub> </td> <td align="center"> <b>Maria Clara Risi</b><br> <sub>Análise e desenvolvimento</sub> </td> </tr> </table>
📚 Referências
KOTLER, Philip. Marketing 4.0. Rio de Janeiro: Sextante, 2017.

SEBRAE. Marketing Digital para pequenas empresas.

ROCK CONTENT. Guia completo de Marketing Digital.

THINK WITH GOOGLE. Tendências de consumo e comportamento digital.

INSTAGRAM BUSINESS. Central de Ajuda para Empresas.

📝 Licença
Este projeto é de caráter acadêmico e foi desenvolvido para fins educacionais.
Sinta-se livre para estudar, adaptar e reutilizar o código como referência.

Distribuído sob a licença MIT. Veja LICENSE para mais informações.

<p align="center"> Feito com 💛 por <b>Larissa</b>, <b>Livia</b> e <b>Maria Clara</b><br> <sub>Projeto de Administração · Tema: Marketing · 2026</sub> </p> ```
