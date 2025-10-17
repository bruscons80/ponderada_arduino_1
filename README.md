# Conceitos Utilizados e Funcionamento

## O que significa IOT?

Segundo a **IBM**, IOT (Internet das Coisas) se refere a uma rede física de dispositivos, veículos e outros objetos que estão diretamente ligados a sensores, software e conectividade a internet, permitindo a interligação de conexões e transmissões de dados. 

## Materiais utilizados para a ponderada e funcionamento:

- Arduino: Uma plataforma de prototipagem eletrônica, composta por hardware (uma placa com microcontrolador) e software (uma IDE para programação). 

- Protoboard: Uma placa responsável por encaixar componentes e criar conexões elétricas temporárias.

- LED: Um diodo emissor de luz.
Perna longa (ânodo) está conectada ao resistor
(lado positivo), Perna curta (cátodo) está conectada ao fio vermelho
(GND).

- Fio Preto (energia positiva):
Leva 5 V até a linha laranja da protoboard.

- Fio Vermelho (GND): Conecta o lado negativo da protoboard ao pino GND
do Arduino e fecha o circuito, permitindo que a corrente
retorne ao ponto inicial.

- Resistor: Reduz a corrente elétrica e evita que o LED queime.

## Funcionamento do código]

```c++
 int ledPin = 8
 ```
 **Coloca o controle do LED no pino 8 do arduino.**

 ```c++
 pinMode (ledPin, OUTPUT)
 ```
**Responsável por botar o port 8 em modo Output**

 ```c++
 digitalWrite(ledPin, HIGH);
 delay(2000);
 digitalWirte(ledPin, LOW);
 delay(1500);
 ```
**Aplica luz alta no LED, bota um delay de 2 segundos, apaga o LED e reinicia o loop depois de 1,5 segundos**


### Link do Tinkercad: https://www.tinkercad.com/things/jyugV5GRVHX/editel?returnTo=%2Fdashboard&sharecode=liX_a-lXnFZWYhEXiIA7qPaiZTMZjqnQTaXlJYt6aeI
