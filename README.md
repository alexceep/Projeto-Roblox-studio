# 🎮 Projeto Roblox Studio – Sistema de Moedas e Super Jump

## 📌 Descrição

Este projeto foi desenvolvido no Roblox Studio com foco na correção e melhoria de dois sistemas principais do jogo:

- 🪙 Sistema de coleta de moedas
- 🚀 Sistema de compra de Super Jump

O objetivo foi corrigir bugs existentes, melhorar a lógica de funcionamento e garantir maior estabilidade e consistência na experiência do jogador.

---

## 🛠️ Problemas Corrigidos

### 🪙 Sistema de Moedas

**Problemas anteriores:**
- Moedas podiam ser coletadas mais de uma vez
- Contador não atualizava corretamente
- Possível conflito entre jogadores

**Correções aplicadas:**
- Implementação de verificação para evitar coleta duplicada
- Atualização segura do leaderstats
- Ajustes na detecção de colisão
- Organização da lógica em scripts mais claros

---

### 🚀 Sistema de Super Jump

**Problemas anteriores:**
- Jogador conseguia comprar sem ter moedas suficientes
- Super Jump não aplicava corretamente
- Compra podia ser repetida infinitamente

**Correções aplicadas:**
- Verificação de saldo antes da compra
- Controle para impedir compras duplicadas
- Aplicação correta do aumento de JumpPower
- Estrutura de validação no servidor para maior segurança

---

## 🧠 Tecnologias Utilizadas

- Roblox Studio
- Lua (Linguagem de Script do Roblox)
- Leaderstats
- RemoteEvents (se aplicável)
- Manipulação de propriedades do Humanoid

---

## 🎯 Objetivo do Projeto

- Melhorar a estabilidade do jogo
- Corrigir falhas de lógica
- Aplicar boas práticas de programação
- Garantir segurança contra exploits básicos

---

## 📷 Demonstração

*(Você pode adicionar aqui prints do jogo ou GIFs)*

---

## 👨‍💻 Autor

Desenvolvido por **Luiza Lopes**

---

## 📄 Licença

Este projeto é apenas para fins educacionais e de estudo.