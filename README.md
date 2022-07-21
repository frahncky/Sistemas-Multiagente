Versão 1.0 

## Sistemas-Multiagente

Algoritmo de Aprendizado por Reforço de Sistema Multiagente para otimização de trajetoria de veículos em aplicações de logistica.

O problema foi modelado da seguinte forma:

1. Cada caminhão é um agente no sistema
2. Cada CD é uma possível ação a ser tomada
3. A recompensa acontece quando todos os caminhões realizam as viagens e ficam vazios. Caso aconteça de os CD ficarem fora do intervalo de estoque, ocorre uma punição alta. Entretanto, se os CD estão dentro do intervalo, ocorre uma bonificação média se o trajeto foi normal ou alta se foi otimizado.
