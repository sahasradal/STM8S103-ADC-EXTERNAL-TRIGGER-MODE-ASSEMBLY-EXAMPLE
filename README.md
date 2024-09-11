# STM8S103-ADC-EXTERNAL-TRIGGER-MODE-ASSEMBLY-EXAMPLE
ADC with EXTERNAL trigger on PB4. analog Input on PC4 AIN2
External trigger signal is applied on PB4 (ADC_ETR pin). ADC input signal on AIN2 PC4. Coversion is done on receiving a high edge on PB4 ADC_ETR pin. Polling mode is used to wait until an EOC flag is set in the 
ADC status register. The results are then stored in SRAM and converted to ASCII and transmitted to UART console at 9600 BAUD. STVD project with assembly code attached. I used an arduino uno blinking at 1 second interval. The LED pin 13 of the UNO is connected to the PB4 ADC_ETR . On each LED ON the ADC conversion happens and value transmitted to console.
