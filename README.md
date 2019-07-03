# Comandos AT - comandos comuns para modens

## Comandos AT

AT - (teste simples)

AT+GMR - (ver versão do firmware)

AT+CWMODE? - (que modo de operação está)

AT+CWMODE=1 - (configura como Station ; 2 = access point ; 3 = both)

AT+CWLAP - (lista as conexões disponíveis)

AT+CWJAP="ArduinoDay","esp826601" - (conecta na rede parametrizada)

AT+CIFSR - (verifica o endereço IP dado)

## Preparação da IDE Arduino

esp8266 arduino github

http://arduino.esp8266.com/stable/package_esp8266com_index.json

## Webserver

const char* ssid = "ArduinoDay";

const char* password = "esp826601";

## IP Fixo

IPAddress ip(192, 168, 1, 12);   //mudar o ultimo digito

IPAddress ip1(192, 168, 1, 1);

IPAddress ip2(255, 255, 255, 0);

//setup após a conexão

WiFi.config(ip, ip1, ip2); 

