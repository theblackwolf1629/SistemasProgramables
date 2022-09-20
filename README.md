# SistemasProgramables-Exposicion de Sensores de PICO

## SSD1306 OLED display

### El nombre de este dispositivo se refiere a que es una pantalla OLED que es manejada por un controlador SSD1306.  
### La pantallas OLED utilizan nodos organicos de emisor de luz capaces de consumir muy poca energía, son muy delgadas y producen una imagen más brillante y nítida que una pantalla LCD ademas de que no requieren luz de fondo ni de filtros. Esto hace que las pantallas OLED sean más eficientes en términos de energía, más fáciles de fabricar y mucho más finas. A parte pueden ser flexibles y transparentes.  
![image](https://user-images.githubusercontent.com/61613146/191343485-8f7992f4-4ec2-4890-a258-61345ba67c2e.png)
### Básicamente lo que hace el SSD1306 es comunicar con el microcontrolador para obtener los datos y enviarlos a la pantalla OLED para que dibuje esos datos. La comunicación entre el SSD1306 y el microcontrolador, ya sea un Arduino o un ESP8266, se realiza mediante SPI o I2C. Generalmente, la comunicación SPI es más rápida que la comunicación I2C. Por el contrario, la comunicación SPI requiere de más pines que la comunicación I2C.  
### Al final una cosa compensa a la otra. Puedes elegir una comunicación más rápida en detrimento del número de pines o puedes elegir liberar más pines en detrimento de la velocidad. No deja de ser una elección personal. Gracias a que el SSD1306 es tan versátil, puedes encontrar pantallas OLED con Arduino con diferentes tamaños y colores.  

|PULGADAS                       |PIXELES                      |
|-------------------------------|-----------------------------|
|   0,69"                       |  128 X 32                   |
|   0,96"                       |  128 X 64                   |

|PARAMETRO                         |VALOR                        |
|----------------------------------|-----------------------------|
|Voltaje de operacion SSD1306      |1,65V a 3,3V                 |
|Voltaje de operación pantalla OLED|7V a 15V                     |
