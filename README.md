# DIO - Trilha .NET - Explorando a linguagem C#

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de explorando a linguagem C#, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Você precisará usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.
O seu programa deverá cálcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

## Regras e validações
- Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
- O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
- Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.

## Diagrama de classes
![image](https://user-images.githubusercontent.com/62121038/210793407-169ab2e1-6a74-4f92-ad33-afb547502b7e.png)


## Resultado
### Caso o número de hospedes for menor que 10
<img width="245" alt="image" src="https://user-images.githubusercontent.com/62121038/210797546-077d6f0f-e319-4e9e-8c91-c1f7fe1f0145.png">

### Caso o número de hospedes for maior que 10, receberá desconto
<img width="209" alt="image" src="https://user-images.githubusercontent.com/62121038/210797787-779bd212-5ca6-49e5-949c-6e409bf19afc.png">
