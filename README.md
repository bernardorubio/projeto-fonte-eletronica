# projeto-fonte-eletronica

## Descrição 

Uma fonte de tensão, projetada pelo nosso grupo, alunos do Bacharelado de Ciências da Computação na Universidade de São Paulo, realizando o projeto da disciplina SSC-0180 do professor Eduardo do Valle Simões, do ICMC-USP. A nossa fonte opera com um transformador 24/1 e, ao ser conectada à uma carga teste de resistência 120 Ohms, gera tensão na faixa de 3-12V, variando de acordo com a configuração do potenciômetro.

## Alunos:
 * Bernardo Acêdo Rubio
 * Samuel Gurgel Araripe
 * Leonardo Cruz Carvalho Ferreira

## Componentes

| Componente      | Qtd.           | Preço  |
| ---------------   |:--------------:| ------:| 
| Capacitor 470μF |       1        | R$2,80 |
| Resistor 4.7k   |       10       | R$0,70 |
| LED Vermelho 5mm|       2        | R$1,00 |
| Resistor 2.2k   |       10       | R$0,70 |
| Resistor 100 Ohm|       2        | R$2,40 |
| Diodo Zener 13V |       2        | R$1,00 |
| Transistor 2N222A  |       10       | R$0,70 |
| Ponte Retif. 2W10M|       1        | R$4,10 |
| Potenciometro B10K |       1        | R$7,00 |
| Protoboard BB-01|       1        | R$23,80 |
| Jumper Macho-Macho |       10        | R$7,00 |
| Total |       --        | R$55,70 |

## Funções

1. Ponte retificadora - É um arranjo de 4 diodos que serve para converter a corrente alternada em uma corrente contínua positiva. Ela encaminha a parte positiva para a mesma polaridade, convertendo então a parte negativa para o polo positivo.

2. Capacitor - Serve para armazenar a energia e, dessa maneira, carregar e descarregar de forma proporcional a tensão, uniformizando variações de tensão e melhorando o funcionamento do sistema.

3. Diodo Zener - Um diodo, tal qual os usados na ponte, mas que opera de forma controlada para, quando acima de uma tensão específica, mantém a tensão entre seus terminais aproximadamente constante.

4. Transistor - Dividido em três partes (Emissor, Base e Coletor), recebe corrente pelo Coletor e emite pelo Emissor, com a relação entre as correntes recebidas ou emitidas sendo diretamente controlada pela Base.

5. Potenciômetro - Um resistor variável, com um cursor que permite variar quanto de corrente será resistida.

6. Resistor - Elemento que se opõe a passagem de corrente com base em uma relação de proporção entre resistência, tensão e corrente (primeira lei de ohm).

## Representações do Circuito

[Representação no Falstad](https://www.falstad.com/circuit/circuitjs.html?ctz=DwYwlgTgBAZgvAIgIwKgFwM6IAwDpsEECsqYIiSeATAVQOx0DM2AHFQGwCcndqIARoiLZUAB0EIALI1QA3CENQBbTEICmAWiQoAfACgoUYLKgAPCu2xRGNKEktRJLEbByoA7vGSoYChJeUAQ1NZCnoEAHp9Q2B3MwsrGysqFhZrGh83KIMjOPNkBydE7ElHZ0yEEWyYvMQUtKTrEvSXLyroowAVeIRmUsaista3KDAAO0RJVAhAnFwkFh4iRiT2FkZtJE52PgB7Oe5ODzAEvmxEDTx2RnZhbCJJKmX2SUllviQsjtiewcbb9gtCrtHI-fKDQYAobAyLfWr+IiA-50KhA1yVWGg+FQwZ0ZpFGHVXI9PGlXEsMnldEgmokilDKAsezQ6mY2n5JmAwYsF4stps4kc3nc3mMCmEuE9Hn9enStH8olgxByxrORIZVmKgAmPXYKJaUCYgKeO1ZUCU+wQWrUMECAFcADZoAXAHUcggGo1QE0w82W622x3OxXwr03NJeyT2CVYkk3RzMzhIVFR00K75uxBhtZQPWopK+i2IAP2p0uzMIbNpNXykZFq020vByX5L0mw3xqhUKaaltZzvdxnbb3dmPs5XDrulSiSZKj3ux-JJlOJzgrtNfUEgHozufTkpWVO+8iVfDYFCjUKnggXjB+FyyLV1Ki4Jx0W50biSbhUGwu+E-gmgK7kBY5GAA5juB5AXY0HSFQYFKsg0FTnYSADj26aLhQcHMto8ZHguMTQPk+HGoOZHWDcvp+JIeI0kYAAyACiAAiO7oUi8aUYR-J+sWjZBhoDpqFqfB+BeIDgSMAh1vwJ54Oe-4cRhdhUMyU6IfCPF4epXLRkRRgkWEGkUXpTSYSMEmEOWShQGMSiIAAXmoYxqBAWgyOiF5gFgyC4HQSDSEQKRbKFhBUJovBQBAfkuBMCAvoQyUpQQ4pQPwV7oT4JzeIqTk7uZqZqcyfSFpaLluR52WKqIaA7hs+a2OhybWGsFQXkoszITZUCiJaeDcHcqXJbeDqIAASmoGC+WggRjCAajKaRNgNCFdiMO+1ghVphWmdOs5pJphnAMZyCHSOB2zpdNE4QxSHoVtjDrUFg7PQhJ3aY8-Qvd93qpLtpF-fUdhvMaAOfTurx7qD+rHVhMT1UDiL-WkQWpKjvqiAlF78God3KP6glllAsh4xc9jzCsjCSOw2hEEQ76baaZMKbgeqcE4LDCDwWx0TtIZQ3DFFczdkNAxjqHo0dKKAxQot9KDGNipZGKKmd0vWPSmu8VZYT3dp5mK8mw5leLYSm80LX5iUcvII1Fkba1Bbm+dGPFTrf6u8mwo2GpwoGQjgphAHwFFYHm7jvbzvaw7s7DGr3wa3HHrW44Xt8X4iIEMtFBx37aevCwds+2SBccGSTglxXjhOE7KZV97ovwUraRFyXcd1zrjdYcAETgBA+hAA)

Schematic:

<img width="1169" height="829" alt="Schematic_FonteEletronica_2026-07-02" src="https://github.com/user-attachments/assets/c496eb23-3edf-4281-9f39-59a6f46ac447" />

PCB:

<img width="621" height="328" alt="PCB_PCB_FonteEletronica_5_2026-07-02_page-0001 jpg" src="https://github.com/user-attachments/assets/7fa424cf-5dde-4583-b4d0-bb4832e98fcd" />

## Vídeo do Circuito:

[Explicação do circuito e os componentes](https://www.youtube.com/shorts/O5V_5XK2mQQ?is=RIVfYznDhTY0lPra)

[Circuito funcionando com voltagem certa](https://youtube.com/shorts/cHcN4smLEQs?is=NMSxgJVY7Om15eZG)


## Cálculos:

$$
\begin{aligned}
V_{\text{fonte}} &= 127\ \text{V (RMS)} \\
V_{\text{sec}} &= 24{,}1\ \text{V (RMS)} \\
V_{2,\text{pico}} &= 34{,}1 - 1{,}4 \approx 32{,}7\ \text{V}
\end{aligned}
$$

$$
\begin{aligned}
I_{\text{LED}}   &= \frac{V_{2,\text{pico}} - V_{\text{LED}}}{R_{\text{LED}}}
  = \frac{32{,}7 - 1{,}7}{5600} \approx 5{,}5\ \text{mA} \\
I_{\text{zener}} &= \frac{V_{2,\text{pico}} - V_{Z}}{R_{\text{zener}}}
  = \frac{32{,}7 - 13}{4400} \approx 4{,}5\ \text{mA} \\
I_{\text{pot}}   &= \frac{V_{2,\text{pico}}}{R_{\text{pot}}}
  = \frac{32{,}7}{9500} \approx 3{,}4\ \text{mA} \\
I_{\text{carga}} &= \frac{V_{Z} - V_{BE}}{R_{\text{carga}}}
  = \frac{13 - 0{,}7}{120} \approx 102\ \text{mA} \\
I_{\text{total}} &= I_{\text{LED}} + I_{\text{zener}} + I_{\text{pot}} + I_{\text{carga}}
  \approx 115{,}8\ \text{mA}
\end{aligned}
$$

$$
\begin{aligned}
V_{\text{ripple}} &= 0{,}10 \cdot V_{2,\text{pico}}
  = 0{,}10 \cdot 32{,}7 \approx 3{,}27\ \text{V} \\
C &= \frac{I_{\text{total}}}{f \cdot V_{\text{ripple}}}
  = \frac{0{,}1158}{120 \cdot 3{,}27}
  \approx 295\ \mu\text{F}
  \;\Longrightarrow\; 470\ \mu\text{F}
\end{aligned}
$$

$$
\begin{aligned}
V_{\text{out}} &= V_{Z} - V_{BE} \approx 13 - 0{,}7 \approx 12{,}3\ \text{V} \\
P_{\text{transistor}} &= (V_{2,\text{pico}} - V_{\text{out}}) \cdot I_{\text{carga}}
  \approx (32{,}7 - 12{,}3)\cdot 0{,}102 \approx 2{,}1\ \text{W}
\end{aligned}
$$
