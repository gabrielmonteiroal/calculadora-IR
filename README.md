# Calculadora de Imposto de Renda em Lisarb

Este exercício de estrutura condicional feito em Java calcula o Imposto de Renda de uma pessoa fictícia no país imaginário de Lisarb. Neste país, todos os habitantes ficam felizes em pagar seus impostos, pois sabem que não existem políticos corruptos e os recursos arrecadados são utilizados em benefício da população.

## Como Usar

1. Certifique-se de ter o Java instalado em seu sistema.
2. Clone este repositório ou baixe o arquivo `calculadora-IR.java`.
3. Compile o código Java:

   ```bash
   javac Main.java
   ```

4. Execute o programa:

   ```bash
   java Main
   ```

5. Insira o salário da pessoa de Lisarb quando solicitado.

   O programa calculará o Imposto de Renda de acordo com a tabela fornecida e exibirá o valor a ser pago com duas casas decimais.

## Tabela de Imposto de Renda em Lisarb

- Até R$ 2000.00: Isento
- De R$ 2000.01 até R$ 3000.00: 8%
- De R$ 3000.01 até R$ 4500.00: 18%
- Acima de R$ 4500.00: 28%

## Exemplos

- Se o usuário inserir `3002.00`, a saída será "Imposto de Renda: R$ 80.36".
  - Explicação: O salário é de R$ 3002.00, então a taxa que incide é de 8% sobre R$ 1000.00 (pois a faixa de isenção vai até R$ 2000.00) mais 18% sobre R$ 2.00.
- Se o usuário inserir `1701.50`, a saída será "Isento de Imposto de Renda".
  - Explicação: O salário é de R$ 1701.50, então está na faixa de isenção.

## Detalhes do Código

- O programa utiliza estruturas condicionais `if-else` para determinar a taxa de imposto de renda de acordo com o salário inserido.
- Os valores e faixas de imposto são baseados nas regras fictícias do país Lisarb, conforme a descrição do problema.
- O valor do imposto de renda é calculado e exibido com duas casas decimais.
---
