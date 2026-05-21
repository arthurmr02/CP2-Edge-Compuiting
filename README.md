# CP2-Edge-Compuiting


EQUIPE: SmartLens  

 

Integrantes:  

Arthur Romão – RM568878  

Anna Carolina – RM570544  

Henrique Ferreira – RM570740  

Henrique Cortez – RM571366  

Vinicius Romão – RM564379 

 

 

Descrição do projeto: 

Este projeto tem como objetivo o desenvolvimento de um sistema inteligente de monitoramento ambiental para a Vinheria Agnello, utilizando conceitos de Edge Computing com Arduino. 

A solução foi projetada para monitorar em tempo real as condições do ambiente da vinheria, realizando leituras de: 

Luminosidade  

Temperatura  

Umidade  

Os dados coletados são processados localmente pelo Arduino e apresentados ao usuário através de: 

LEDs indicadores  

Buzzer sonoro  

Display LCD 

O sistema foi desenvolvido em duas etapas evolutivas: 

CP1: implementação do monitoramento de luminosidade com LDR, LEDs e buzzer  

CP2: expansão do sistema com sensor DHT11 e display LCD para exibição das informações ambientais em tempo real  

O objetivo principal é garantir condições adequadas de armazenamento para os vinhos, evitando perdas de qualidade causadas por fatores ambientais inadequados. 

 

Objetivo 

O sistema foi desenvolvido para monitorar continuamente as condições do ambiente e alertar o usuário sempre que os parâmetros estiverem fora dos níveis considerados ideais. 

As funcionalidades incluem: 

Monitoramento de luminosidade  

Monitoramento de temperatura  

Monitoramento de umidade  

Sinalização visual através de LEDs  

Sinalização sonora através de buzzer  

Exibição dos dados e status no display LCD 

 

Tecnologias Utilizadas 

Arduino UNO  

Sensor LDR (Light Dependent Resistor)  

Sensor DHT11  

Display LCD 16x2  

LEDs (verde, amarelo e vermelho)  

Buzzer  

Resistores  

Plataforma Wokwi  

Linguagem C/C++ (Arduino IDE) 

Funcionamento do Sistema  

O sistema realiza monitoramento contínuo do ambiente através dos sensores conectados ao Arduino. 

O sensor LDR realiza a leitura da luminosidade do ambiente.  

O sensor DHT11 realiza a leitura da temperatura e da umidade.  

O Arduino processa todas as informações recebidas.  

O sistema classifica o estado atual do ambiente.  

O status é exibido no display LCD.  

LEDs e buzzer são acionados conforme as condições detectadas. 

 

Simulação 

O projeto foi desenvolvido e validado em ambiente de simulação utilizando: 

Wokwi –  https://wokwi.com/projects/461411324381726721
 



 

Estrutura Lógica do Sistema  

O sistema opera através de leituras contínuas dos sensores utilizando estruturas condicionais para definir o comportamento dos componentes de saída. 

A lógica principal funciona da seguinte forma: 

Leitura da luminosidade via LDR  

Leitura da temperatura e umidade via DHT11  

Comparação com limites definidos  

Atualização do LCD  

Controle dos LEDs  

Acionamento do buzzer em situações críticas 
