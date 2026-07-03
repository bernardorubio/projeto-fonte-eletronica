# Projetos Eletrônica SCC-0180

# Fonte de Tensão

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

[Representação no Falstad](https://www.falstad.com/circuit/circuitjs.html?ctz=DwYwlgTgBAZgvAIgIwKgFwM6IAwDpsEECsqYIiSeATAVQOx0DM2AHFQGwCcndqIARoiLZUAB0EIALI1QA3CENQBbTEICmAWiQoAfACgoUYLKgAPCu2xRGNKEktRJLEbByoA7vGSoYChJeUAQ1NZCmcEAHp9Q2B3MwsrGysqFhZrGh83KIMjOPNkBydE7ElHcNcEEWyYvMQUtKTrEvSXLyroowAVeIRmUsaista3KDAAO0RJVAhAnFwkSU4qIkYmJEZpFMYiXigQAHs57k4PMAS+bEQNPBZOEu4nFKQWOiddkCQsjtiewcb2IjsFqZSqRb61KTOIZQAFAoog9o5H75WEtGF0KjAiqImo9VGDOjNeHYsFIiGE0oEliU8ptUm4-J0anQlj2IYI+m5HqsuFQljsGnDUHVLn5fmCqDi6zUjki5GIKWMZmKjIkuUQlVWZyJVV0uUAEzxGLRTCBy3YHKgSkOCH1ahggQArgAbNCc4CGsUEE2MM2Ay3WxB2h0ut3qnqm6zsNKRyT2WXgiO+xxszhITFxi1q76exCR31pdjGpIBm3Bp2u925hD56OS70lklWsv2ithxOM5PmqCRqhUKbZslJs39yWcEcDvUdhXjqB90qUSTJfsJof5NMZ1NLFNZqdIkA9RfLhclKyZy3kSr4AiSXZgUJXggoKAYPwuWT6upEXBK25Uez-ownBECu4brtumZ2KeO6rjEADmh7QZBR6ODYsGihQ0HznY6wTuh8rIEhbLaMm56DjE0D5CRE44cmjC+pafi3gQ7oADIAKIACKHrh1jJtRMFNoGtqtqGGjOmo+p8H4z4gHBIwCCMSj8JeeDYCgYEULx2Hpmy874RCAnIf+cLxuRRiURQJlzqOulAn0jF1DQOJGPqShQGMSiIAAXmoYxqBAWgyBUz5gFgyC4HQCzbE8SysoQVCaLsEDhS4EwIFQ16ENlOUylA-APusPhnN4creYe1nGWyDlCTavn+YFRVyqIaCHow6ZousHUFiCz5KLMhGEGINpqdgJAvs6iAAEpqBgYVoIEYwgGo7qGTYDQgXYqz2SBBkVXptlLmk+nmcAlnIEdNkLpIS5XY5g2rW1dA7ZiCyjjFe1UZI72bW9pT1J9FDff9qR2JIgJzqkgMXbdOm3piJ17jErVfRD9Rg6DANNqI6XPvwaiYS4wnlqGcj41cmXg1w7AcDsvr0OOZOqZFCxMjwNjRsISDcI9X3GnDmMrqdhlOMdh2Yxi0MLKDfQYw0eVIxZh6i9K12g2RdJQDJGSacg1my+ms41YrBGG-ZzRdZixtfGuFDtVbFv21iJsi+rxEq5sUscJSNh2N7gkuxVAo7n7bIazbDJ291zKW44LGnedsdLlYSdoU2fh9ixuup69Ts3SwXvB5sftF04heUk4W0dfnUse770tpDXwttdXlcN44ZeDsAETgBA+hAA)

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






# Arduino: Sensor de ré 

## Código do projeto

```
int trigPin = 3; // sensor ultrassônico
int echoPin = 4; // sensor ultrassônico
int ledPin1 = 8;   // mais longe(VERDE)
int ledPin2 = 9;
int ledPin3 = 10;  // mais perto
int buzzerPin = 11;

long int duracao;
long distancia;

void setup() {
  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);
  pinMode(ledPin1, OUTPUT);
  pinMode(ledPin3, OUTPUT);
  pinMode(buzzerPin, OUTPUT);
}

void loop() {
  // disparar sensor ultrassônico
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2);
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin, LOW);

  duracao = pulseIn(echoPin, HIGH);
  distancia = (duracao / 2) / 29.1;

  // leitura inválida ou muito longe
  if (distancia <= 0 || distancia > 24) {
    digitalWrite(ledPin1, LOW);
    digitalWrite(ledPin2, LOW);
    digitalWrite(ledPin3, LOW);
  }
  else if (distancia <= 8) {
    digitalWrite(ledPin1, HIGH);
    digitalWrite(ledPin2, HIGH);
    digitalWrite(ledPin3, HIGH);
   }
  else if (distancia <= 16) {
    digitalWrite(ledPin1, HIGH);
    digitalWrite(ledPin2, HIGH);
    digitalWrite(ledPin3, LOW);
  }
  else if (distancia <= 24) {
    digitalWrite(ledPin1, HIGH);
    digitalWrite(ledPin2, LOW);
    digitalWrite(ledPin3, LOW);
  }

  if (distancia > 0 && distancia <= 24){
    int tempoBipe = map(distancia, 2, 24, 40, 350);
    tempoBipe = constrain(tempoBipe,40, 350);

    // executa o bipe
    digitalWrite(buzzerPin, HIGH);
    delay(30);
    digitalWrite(buzzerPin, LOW);
    delay(tempoBipe);
  }
  else {
    digitalWrite(buzzerPin, LOW);
  }
  
}
```

## Representação do Circuito

Arduino:



## Vídeo e detalhamento

[Link do vídeo mostrando o projeto](https://youtube.com/shorts/il4gO5-YKGo?is=HdYry4UqaUWrtvBF)


* O nosso projeto se trata da simulação do sensor de ré de um carro utilizando uma placa arduino UNO. Para isso, os principais componentes foram: um sensor ultrassônico HC-SR04, um buzzer ativo e 3 leds 5mm, sendo 1 verde e 2 vermelhos. A função de cada peça é:

### Sensor HC-SR04:

O sensor é, como o coração do sistema, a peça que usa ondas sonoras para medir a distância até algum objeto na direção que ele aponta. O software do sensor de ré reside basicamente em programar para quais distâncias do sensor os leds acendem e o buzzer apita.

### Buzzer ativo:

O buzzer é a parte que adere mais realidade e aplicabilidade ao projeto. Ele serve para gerar um apito períodico que torna usável o sensor de ré mesmo que não esteja olhando-o. O buzzer, como citado, é ativo, o que significa que você pode configurar a frequência do barulho, mas somente isso. Em contraste, em um buzzer passivo seria possível configurar, no código, o tom e a nota musical do barulho, que, como não mudaria nada no nosso projeto, não foi usado.

### LED's coloridos:

Os leds foram usados para aderir sentido visual ao projeto. O led verde acende quando o objeto está a distância satisfatória do sensor. Os dois leds vermelhos acendem (não simultaneamente) conforme se aproxima o objeto do sensor. A cada led foi aderido um resistor para controlar a energia e evitar que o led queime.

