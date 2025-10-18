# Ponderada-arduino

Esse repositório aborda a entrega da ponderada da semana 1. A seguir, estão as duas etapas da entrega:

## Parte 1

A primeira parte da ponderada pede que o led interno do Arduíno Uno pisque inefinidamente, para isso, foram realizados os seguintes procedimentos:

A seguir, segue o código utilizado para realizar o blik do led interno do arduíno:

<img width="1837" height="829" alt="Captura de tela 2025-10-17 091807" src="https://github.com/user-attachments/assets/aba71ccf-17c8-4757-8fa3-49a74dc66395" />

O código começa com a declaração da variável led_interno, que é igualada à saída que o led está ligado, em seguida, a função void setup seleciona o led_interno como output, e por fim, a função void loop determina o tempo que a luz deve ficar ligada e acesa, no caso, 1000 milissegundos, fazendo com que esse processo seja cíclico.

A seguir, está a imagem do arduíno com a luz acesa, demonstrando que o sistema funcionou:

![Imagem do WhatsApp de 2025-10-17 à(s) 09 17 52_b78402b2](https://github.com/user-attachments/assets/d87e9851-17b6-410a-bbbb-98255ff72353)

## Parte 2

A segunda etapa da ponderada requer um sistema que faça uma lâmpada LED piscar, para isso, foram realizados os seguintes processos:

Inicialmente, o sistema é montado no Tinkercad, utilizando a ferramenta para fazer o sistema que faz a conexão do arduíno, com a protoboard, resistência e por fim, o led.

A seguir, está a imagem que mostra o sistema na plataforma:

<img width="1354" height="580" alt="Captura de tela 2025-10-17 093835" src="https://github.com/user-attachments/assets/9875ac20-3b5d-4d39-ad56-b04471ca986e" />

Na imagem é possível visualizar o arduíno, os jumpers que estão ligando ele à protoboard e os componentes necessários para seu funcionamento. Vale ressaltar que esse sistema é totalmente funcional. A seguir, está o link público para acesso do projeto:

<https://www.tinkercad.com/things/4CS8haHfkqh/editel?sharecode=7LalXyNDchfO-_HLaSnqNBYnkYnvfRhPEvjwZ2_hOd0>

Em seguida, o projeto foi para o ambiente real, sendo utilizados os componentes reais. Assim, para que o led pisque como o planejado, foi feito o seguinte código:

x  <img width="1836" height="831" alt="image" src="https://github.com/user-attachments/assets/1500c784-7212-4f64-891f-4da85dc5a773" />

Esse código segue a mesma linha de raciocíno do primeiro, com a pequena diferença da variável escolhida, antes ela estava ligada ao led interno do arduíno, agora ela está ligada à porta 8.

Por fim, o sistema montado:

![Imagem do WhatsApp de 2025-10-18 à(s) 00 15 43_5a165f3e](https://github.com/user-attachments/assets/af472939-cc71-49ae-a76b-28977e3b0e19)

Com essa monstagem o objetivo da ponderada foi alcançado, sendo possível visualizar a montagem e funcionamento dos sistemas necessários.
