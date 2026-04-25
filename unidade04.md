## Álgebra Booleana e Lógica Digital

Aqui iremos compartilhar um conteúdo sobre portas lógicas, que são responsáveis por todo circuito de informação binária até chegar ao usuário final.

As principais portas lógicas são: AND, OR, NOT, NAND, NOR, XOR e XNOR.

### Tabela da Verdade (resumo)

* AND → só é verdadeiro se ambas as variáveis forem verdadeiras
* OR → é verdadeiro se pelo menos uma variável for verdadeira
* NOT → inverte o valor (0 vira 1 e 1 vira 0)
* NAND → é o oposto do AND
* NOR → é o oposto do OR
* XOR → verdadeiro quando as entradas são diferentes
* XNOR → verdadeiro quando as entradas são iguais

### Álgebra Booleana

Na álgebra booleana temos algumas operações principais:

* OR (soma lógica): S = A + B  
* AND (multiplicação lógica): S = A · B  
* NOT (negação): S = ¬A  
* Dupla negação: ¬¬A = A  

### Teorema de De Morgan

O Teorema de De Morgan diz que:

¬(A + B) = ¬A · ¬B  
¬(A · B) = ¬A + ¬B  

### Regra importante

- “+” não vira menos (−)
- “+” vira AND (·)
- “·” vira OR (+)
- e todas as variáveis são negadas

### Exemplo

¬(0 + 1)

Aplicando De Morgan:

= ¬0 · ¬1  
= 1 · 0  
= 0  

### Conclusão

O Teorema de De Morgan permite transformar expressões lógicas invertendo as operações e negando todas as variáveis.
