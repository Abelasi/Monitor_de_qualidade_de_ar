Monitor de qualidade de ar - Projeto IoT

Introdução:

Este projeto utiliza de uma placa NodeMCU modelo ESP8266 com conexão WiFi integrada, sensor de gás MQ135, sensor de temperatura e umidade DH11 e painel OLED, a integração desses dispositivos cria um aplicativo de Internet das Coisas (IoT). Para troca de dados, foi utilizado o protocolo MQTT (Message Queuing Telemetry Transport).

Recursos:

- Permite medir a temperatura ambiente em graus Celsius (ºC)
- Mede a umidade relativa do ar
- Sensor de gás, mostra a cocentração de gases nocivos
- Conectividade WiFi: conexão a uma rede Wi-Fi para enviar / receber dados para um servidor ou serviço online

Componentes de hardware: 

1. NodeMCU placa de desenvolvimento;
2. Sensor de gás MQ135;
3. Sensor de Temperatura e umidade DH11;
4. OLED display SSD1306

![IoT_img](https://github.com/Abelasi/Monitor_de_qualidade_de_ar/assets/86491294/c6bb7a9c-d127-44ac-97e0-c1bb029085bb)

Configuração do Hardware: conexão dos componentes com a placa

- Sensor DH11: VCC - 3V3, GND - GND, DATA - D4
- Sensor MQ135: A0 - A0, GND - GND, VCC - 3V3
- Display OLED: GND - GND, VCC - 3V3, SDA - D1, SCL - D2

Requerimentos de software:

1. Arduino IDE: para programação da placa NodeMCU
2. MQTT biblioteca: para realizar conexão com o broker 
3. Adafruit SSD1306 biblioteca: interface do display OLED
4. DHT biblioteca: para comunicar-se com o sensor de temperatura e umidade

