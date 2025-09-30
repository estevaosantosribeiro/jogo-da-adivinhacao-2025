# Jogo de Adivinhação - Angular

## Descrição
Este projeto é um **jogo de adivinhação** desenvolvido com **Angular**.  
O objetivo é adivinhar o número secreto dentro de um intervalo, com base em dicas fornecidas pelo sistema.  
O jogador pode escolher entre três níveis de dificuldade e acompanhar sua pontuação a cada tentativa.

---

## Funcionalidades
- Seleção de **nível de dificuldade**: Fácil, Médio ou Difícil.
- Dicas automáticas indicando se o número secreto é **maior ou menor** que o digitado.
- Sistema de **pontuação dinâmica**, com descontos conforme a distância entre o número escolhido e o número secreto.
- Exibição de **tentativas restantes**.
- Botão de **reinício** do jogo.

---

## Regras do Jogo
- **Fácil**  
  - Intervalo: `1 a 10`  
  - Tentativas: `3`  

- **Médio**  
  - Intervalo: `1 a 50`  
  - Tentativas: `6`  

- **Difícil**  
  - Intervalo: `1 a 100`  
  - Tentativas: `7`  

A pontuação inicial é **100 pontos** e diminui conforme a diferença entre o número digitado e o número secreto:
- Diferença ≥ 10 → `-10 pontos`  
- Diferença ≥ 5 → `-5 pontos`  
- Diferença < 5 → `-2 pontos`  

---

## Tecnologias Utilizadas
- [Angular](https://angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Bootstrap](https://getbootstrap.com/) (para estilos)

---

## Como Executar
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd nome-do-projeto
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

4. Rode o servidor de desenvolvimento:
   ```bash
   ng serve
   ```

## Observações

Este é um projeto simples criado com foco em prática e aprendizado de Angular.
Futuramente, podem ser adicionados testes automatizados, melhorias de UI/UX e persistência de pontuação.
