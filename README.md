Tema: Operações de um E-commerce

1. Objetivo da Atividade

Aplicar os conceitos de funções, imutabilidade, condicionais e listas em Clojure, desenvolvendo pequenos algoritmos que simulam situações reais de um sistema de e-commerce.

O estudante deverá implementar todas as funções dentro da função principal -main, de acordo com o modelo trabalhado em sala.

2. Competências Desenvolvidas

* Compreender o uso de funções em Clojure
* Aplicar o conceito de imutabilidade de variáveis
* Utilizar estruturas condicionais e listas
* Simular operações básicas de um sistema comercial

3. Contextualização

Imagine que você está desenvolvendo a parte lógica de um sistema de vendas online.
Seu sistema deverá realizar cálculos de valores, aplicar descontos, calcular impostos e exibir produtos disponíveis.

4. Atividades Práticas

Exercício 1 – Cálculo do total da compra

Crie uma função chamada total que receba o preço e a quantidade de um produto e retorne o valor total da compra.
Exiba o resultado no terminal.

Exemplo de execução:

```
Total da compra é: 150
```

Exercício 2 – Desconto

Crie uma função total-com-desconto que:

* Calcule o total da compra;
* Se o total for maior que 100, aplique 10% de desconto.

Exemplo de execução:

```
Valor final: 135.0
```

Exercício 3 – Imposto sobre o produto

Crie uma função preco-com-imposto que aplique um imposto de 8% sobre o valor de um produto e exiba o preço final com imposto incluso.

Exemplo de execução:

```
Preço final com imposto: 108.0
```

Exercício 4 – Frete grátis

Crie uma função valor-final que adicione R$20,00 de frete caso o total da compra seja menor ou igual a 200.
Se for maior, o frete é grátis.

Exemplo de execução:

```
Valor final com frete: 260
```

Exercício 5 – Lista de produtos

Crie uma lista com 4 produtos e use um doseq para exibir todos os produtos disponíveis.

Exemplo de execução:

```
Lista de produtos disponíveis:
- Camisa
- Tênis
- Boné
- Relógio
```

Desafio (opcional) – Combinar tudo

Crie uma função total-final que:

* Calcule o subtotal (preço × quantidade);
* Aplique o desconto, o imposto e o frete;
* Retorne o valor final da compra.

Exemplo de execução:

```
Valor final da compra: 254.4
```

5. Estrutura de código sugerida

```clojure
(ns ecommerce.core
  (:gen-class))

(defn -main []
  (defn nome-da-funcao [parametros]
    ;; lógica da função aqui
  )
  
  ;; chamadas de exemplo
  (println (nome-da-funcao argumentos)))
```

6. Entrega

* Formato: arquivo .clj
* Nome do arquivo: atividade_ecommerce.clj
* Forma de envio: subir no GitHub ou enviar por e-mail
* Prazo: (inserir data definida pelo professor)

7. Critérios de Avaliação

| Critério                               | Pontos     |
| -------------------------------------- | ---------- |
| Correção dos cálculos e lógica         | 4 pts      |
| Uso correto de funções e imutabilidade | 3 pts      |
| Organização e clareza do código        | 2 pts      |
| Execução completa e sem erros          | 1 pt       |
| **Total**                              | **10 pts** |
