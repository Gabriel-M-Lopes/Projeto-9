# Projeto 09 - Calculadora de IMC

Este projeto é uma calculadora de IMC (Índice de Massa Corporal) desenvolvida como parte do curso Explorer da Rocketseat. O objetivo principal é praticar conceitos de HTML, CSS e JavaScript, além de aplicar boas práticas de organização de código e usabilidade.

---

## Funcionalidades

- **Entrada de Dados:** O usuário informa seu peso (kg) e altura (cm).
- **Validação:** O formulário aceita apenas números. Caso contrário, exibe um alerta de erro.
- **Cálculo do IMC:** O IMC é calculado automaticamente ao enviar o formulário.
- **Exibição do Resultado:** O resultado é mostrado em um modal, que pode ser fechado pelo usuário.
- **Acessibilidade:** O modal pode ser fechado pressionando a tecla `Esc`.

---

## Estrutura dos Arquivos

- **index.html:** Estrutura da página, incluindo formulário, modal e alertas.
- **style.css:** Estilização visual, responsividade e animações.
- **js/script.js:** Lógica principal do formulário, cálculo do IMC e integração com modal/alerta.
- **js/modal.js:** Controle de abertura/fechamento do modal.
- **js/alert-error.js:** Controle de exibição do alerta de erro.
- **assets/**: Imagens e ícones utilizados na interface.

---

## Lógica de Funcionamento

1. **Formulário:** O usuário preenche peso e altura e clica em "Calcular IMC".
2. **Validação:** O JS verifica se os valores são válidos (números e não vazios).
3. **Erro:** Se inválido, exibe alerta vermelho no topo da tela.
4. **Cálculo:** Se válido, calcula o IMC usando a fórmula:
   ```
   IMC = peso / (altura/100)^2
   ```
5. **Modal:** Exibe o resultado em um modal centralizado.
6. **Fechamento:** O modal pode ser fechado pelo botão de fechar ou tecla `Escape`.

---

## Pontos de Aprendizado

- Manipulação do DOM com JavaScript puro.
- Modularização do JS (separação em arquivos para modal e alerta).
- Uso de variáveis CSS e responsividade.
- Boas práticas de UX: feedback visual para erros e facilidade de fechar o modal.
- Utilização de transições e animações para uma interface mais agradável.

---

## Como Executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em seu navegador.
3. Preencha os campos e utilize a calculadora!

---

## Melhorias Possíveis

- Adicionar categorias de IMC (baixo peso, normal, sobrepeso, etc).
- Permitir entrada de altura em metros.
- Exibir histórico de cálculos.
- Melhorar acessibilidade para leitores de tela.

---

Projeto desenvolvido para fins de estudo e prática de front-end.
