# DEAP-Otimizacao

Neste notebook eu quero mostrar a utilização de um framework para computação evolucionária chamado DEAP(Distributed Evolutionary Algorithms in Python). Como o nome já diz é uma lib de algoritmos evolucionários que podem ser rodados de forma distribuidas. Ah, e é em Python! =)

Descobri esse framework quando fui buscar uma solução(em Python) que me auxiliasse em alguns trabalhos da disciplina de Computação Evolucionária que estava fazendo no trabalho. Confesso que no inicio demorei para pegar o jeito, pois a biblioteca tem uma forma peculiar de definir os operadores e funções. Porém depois de compreendido, não quis outra vida! se torna natural pensar nas soluções. Just sit and code!

O que coloco abaixo é um 'Toy Problem' para um Tech Club da empresa. 

# DESCRIÇÂO DO PROBLEMA
Você gerencia uma fábrica de garrafas plásticas que tem apenas uma máquina extrusora. Esta máquina pode funcionar até 60 horas por semanda, isto é, 6 dias por semana com jornada de 10 horas por dia. A máquina é capaz de produzir dois tipos de garrafas plásticas: tipo “leite” e tipo “suco”. Toda a produção semanal de garrafas plásticas é armazenada temporariamente num depósito. No domingo toda a produção é despachada para os compradores e o depósito é esvaziado completamente.

A linha de produção leva 6 horas para produzir 100 garrafas tipo leite e 5 horas para produzir 100 garrafas tipo suco. Cada Carrafa tipo leite ocupa 10 unidades cúbicas de espaço no depósito, enquanto que a garrafa de tipo suco ocupa 20 unidades cúbicas. O depósito tem capacidade máxima de 15000 unidades cúbicas.

A contribuição no lucro final da empresa por garrafa tipo leite é de 5 unidades monetárias e por garrafa tipo suco é de 4,5. O departamento de vendas tem contratos de fornecimento capazes de absorver toda a produção possível de garrafas tipo suco, porém tem compradores somente para 800 garrafastipo leite por semana.

Você deve estabelecer qual é o plano de produção mais adequado para maximizar o lucro total da empresa, isto é, quantas garrafas tipo Leite e quantos tipoo Suco devem ser produzidas semanalmente.
