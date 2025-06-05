2ESP32 Despertador:
Projeto de despertador inteligente utilizando dois microcontroladores ESP32, com comunicação via Wi-Fi, display LCD, relógio de tempo real (RTC) e motor vibratório para alarmes táteis.

Objetivos:
Desenvolver um sistema de alarme distribuído baseado em ESP32, voltado para o público idoso, que muitas vezes esquece de tomar seus remédios. O sistema exibe a hora em um display LCD,
armazena alarmes com precisão usando um módulo RTC e alerta o usuário por meio de vibração, ativada remotamente por uma pulseira conectada via rede local.
 
Funcionalidades:
Hora precisa com módulo RTC DS1307

Display LCD via interface I2C

Comunicação Wi-Fi entre os ESP32 (um como servidor, outro como cliente)

Configuração remota via interface HTTP

Alarme com motor vibratório

Distribuição de tarefas entre dois ESP32:

ESP1: controle de tempo, display e alarmes

ESP2: acionamento do motor

Componentes Utilizados:
2x ESP32
1x Display LCD 16x2 (I2C)
1x RTC DS1307 com bateria
1x Motor vibratório
Jumpers e protoboard
