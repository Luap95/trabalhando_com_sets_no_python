# Trabalhando com Sets no Python

Este notebook explora o conceito e a utilização de **Sets** (conjuntos) na linguagem de programação Python. Sets são coleções não ordenadas de itens únicos, úteis para operações matemáticas de conjunto, como união, interseção, diferença e disjunção.

## Conteúdo do Notebook

### 1. Criação dos Sets

Nesta seção, abordamos diferentes maneiras de criar conjuntos em Python:

-   **Utilizando as chaves `{ }`:** Demonstra a criação direta de sets, a capacidade de armazenar elementos de diferentes tipos de dados (heterogêneos) e a característica de que sets não são indexáveis (não suportam subscrição por índice).
-   **Utilizando listas e a função `set()`:** Mostra como converter uma lista existente em um set, eliminando automaticamente elementos duplicados.
-   **Trabalhando com elementos repetidos:** Ilustra como sets garantem a unicidade dos elementos, removendo duplicatas ao serem criados a partir de coleções com itens repetidos, e o uso da função `len()` para verificar o número de elementos únicos.

### 2. Operações com Sets

Esta seção explora as principais operações que podem ser realizadas com sets, utilizando exemplos práticos com conjuntos de acessórios de carros:

-   **Disjunção (`set.isdisjoint()`):** Verifica se dois sets não possuem elementos em comum.
-   **Interseção (`&` ou `set.intersection()`):** Retorna um novo set contendo apenas os elementos que são comuns a todos os sets envolvidos.
-   **União (`|` ou `set.union()`):** Retorna um novo set contendo todos os elementos únicos de todos os sets envolvidos.

### 3. Performance

Esta parte do notebook compara a performance de busca de elementos (usando o operador `in`) em diferentes estruturas de dados em Python:

-   **Sets:** Demonstra a alta eficiência da busca em sets, devido à sua implementação baseada em tabelas hash.
-   **Listas:** Compara a busca sequencial em listas, que tende a ser mais lenta para grandes volumes de dados.
-   **Tuplas:** Similar às listas em termos de performance de busca.

Os resultados mostram claramente a vantagem de performance dos sets para operações de verificação de pertencimento, especialmente com um grande número de elementos.
