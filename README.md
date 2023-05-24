Monitor de qualidade de ar - Projeto IoT

Introdução:

Este projeto utiliza de uma placa NodeMCU modelo ESP8266 com conexão WiFi integrada, sensor de gás MQ135, sensor de temperatura e umidade DH11 e painel OLED, a integração desses dispositivos cria um aplicativo de Internet das Coisas (IoT). Para troca de dados, foi utilizado o protocolo MQTT (Message Queuing Telemetry Transport).

Componentes de hardware: 

1. NodeMCU placa de desenvolvimento;
2. Sensor de gás MQ135;
3. Sensor de Temperatura e umidade DH11;
4. OLED display SSD1306

Requerimentos de software:

1. Arduino IDE: para programação da placa NodeMCU
2. MQTT biblioteca: para realizar conexão com o broker 
3. Adafruit SSD1306 biblioteca: interface do display OLED
4. DHT biblioteca: para comunicar-se com o sensor de temperatura e umidade

