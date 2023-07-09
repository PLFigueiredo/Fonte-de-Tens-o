# Fonte de Tensão

# Introdução
Projeto realizado para a disciplina SSC0180 (Eletrônica para Computação) do Bacharelado em Ciências de Computação do Instituto de Ciências Matemáticas e de Computação (ICMC) da Universidade de São Paulo (USP). O trabalho foi proposto e supervisionado pelo Prof. Dr. Eduardo do Valle Simões no 1º semestre de 2023.

# Resumo
Este projeto propõe a construção de uma fonte de tensão ajustável de 3V a 12V com capacidade de 100mA. Essa fonte opera a partir de uma corrente alternada e, por meio da disposição especial dos componentes, deve fornecer uma corrente de saída devidamente regulada.

# Tabela de Componentes
| Componentes  | Preço |
| ------------- | ------------- |
| Diodo  | R$0,20 (x10)  |
| Capacitor 470uF  | R$1,20  |
| Diodo Zener 13V | R$0,50  |
| LED  | R$0,50  |
| Resistor 1,5K  | R$0,35 |
| Resistor 1K  | R$0,35 |
| Resistor 2,2K  | R$0,35 |
| Potenciômetro B5K  | R$7,00  |
| Transistor 2N2222A 60V | R$2,00  |
| **Valor total**  | **R$14,25** |

Obs: Para o circuito precisamos de apenas 4 diodos para a ponte retificadora, mas o pacote comercial continha 10 unidades.
# Funções dos Componentes
* **Diodo**: permite a passagem de corrente em somente um sentido. No projeto, um conjunto de diodos formam uma ponte de diodos, a qual possibilita o abastecimento do circuito em ambos os sentidos da corrente alternada.

* **Capacitor**: armazena carga elétrica nos ciclos de corrente alternada e libera corrente quando sua tensão é maior do que aquela transmitida da fonte. O capacitor descarrega ao inverter o ciclo.
  
* **Diodo Zener de 13V**: regula a tensão de saída máxima do circuito. Se a tensão de chegada é menor que 13V, não há passagem de corrente. Caso contrário, o diodo permite a passagem de corrente limitada a 13V.
  
* **Resistor**: limita a quantidade de corrente que é transmitida pelo circuito, permitindo que outros componentes recebem a quantia idela de corrente elétrica.
  
* **Potenciômetro**: resistor particular que permite o ajuste da tensão da fonte entre 3V e 12V.
  
* **Transistor**: permite a passagem ajustável de corrente elétrica.
# Cálculos

# Simulação no Falstad
![01955c9b-76a4-4a1c-96ba-4d5536e8c2f3](https://github.com/PLFigueiredo/Fonte-de-Tensao/assets/70961838/38ebda06-35dd-4e35-afec-c97e99d3a937)
# Circuito esquemático da PCB

# Vídeo de apresentação

# Alunos
- Arthur Trottmann Ramos
- João Pedro Viguini T. T. Correa
- Nicolas Carreiro Rodrigues
- Pedro Lucas Figueiredo Bahiense


