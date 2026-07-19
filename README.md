# ⚡ Nort Camp - Pro Esports Platform

> Plataforma completa e interativa para gerenciamento de campeonatos de E-sports (como Valorant, CS2, Free Fire, etc.), projetada para organizadores de torneios e transmissões ao vivo.

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-success)
![Tecnologia Principal](https://img.shields.io/badge/Tech-Vanilla_JS_%7C_HTML_%7C_CSS-blue)

---

## 📖 Índice

* [Sobre o Projeto](#-sobre-o-projeto)
* [Principais Funcionalidades](#-principais-funcionalidades)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Como Executar o Projeto](#-como-executar-o-projeto)
* [Como Usar a Plataforma](#-como-usar-a-plataforma)
* [Contato](#-contato)

---

## 🎯 Sobre o Projeto

O **Nort Camp** foi desenvolvido para simplificar a gestão de torneios de jogos eletrônicos. A aplicação funciona de forma 100% local no navegador (client-side), utilizando o `LocalStorage` para armazenar dados de times, jogadores, pontuações e chaves. 

A plataforma possui duas visões principais:
1. **Painel do Administrador:** Onde a mágica acontece. Permite configurar as regras do torneio, registrar times, sortear chaves e computar os resultados e kills de cada partida.
2. **Modo Público/Transmissão:** Uma visão limpa, ideal para ser exibida em telões durante eventos presenciais ou capturada pelo OBS Studio para transmissões ao vivo, escondendo os botões de edição.

## ✨ Principais Funcionalidades

* **⚙️ Configuração Personalizada:** Defina o jogo do torneio, o valor da premiação, e quanto vale cada Vitória e cada Kill (Abate). A matemática é feita automaticamente.
* **👥 Gestão de Equipes e Line-ups:** Cadastre organizações, adicione escudos personalizados, nomes dos jogadores e fotos de perfil.
* **🏆 Chaveamento Algorítmico (Bracket):** Geração automática e aleatória de chaves de torneio para 4, 8 ou 16 equipes (Semifinais, Quartas ou Oitavas).
* **⚔️ Computação de Partidas:** Sistema intuitivo para declarar o time vencedor e registrar as kills individuais de cada membro da line-up após as partidas.
* **📊 Leaderboards Dinâmicos:** 
  * Ranking Geral de Equipes (Pontos Totais, Partidas, Vitórias, Derrotas).
  * Ranking de Top Fraggers (Os maiores matadores individuais do torneio).
* **🔄 Sistemas de Reset:** Opção de zerar apenas as pontuações e chaves (mantendo os times para uma nova temporada) ou realizar um *Hard Reset* para limpar o banco de dados completamente.

## 💻 Tecnologias Utilizadas

Este projeto não depende de frameworks pesados ou back-end complexo. Foi construído com:

* **HTML5:** Estrutura semântica do painel.
* **CSS3:** Estilização moderna com variáveis (Custom Properties), CSS Grid, Flexbox e visual Dark Mode focado no nicho gamer.
* **JavaScript (Vanilla ES6):** Toda a lógica de chaveamento, cálculo de pontos e manipulação da DOM.
* **Web Storage API (LocalStorage):** Persistência de dados local, garantindo que você não perca o progresso se atualizar a página acidentalmente.

## 🚀 Como Executar o Projeto

Como o projeto é totalmente *Client-Side*, não há necessidade de instalar dependências via Node ou configurar servidores.

1. Clone este repositório:
```bash
https://caioviniciusx32.github.io/Nort-Camp/
