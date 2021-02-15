# ESP32 IP-CAM with facial recognition and Whatsapp Notification using Twilio API 

## SW Requirements
1.Arduino INO
2.VCP Driver (Virtual COM port)
3.Add-on board https://dl.espressif.com/dl/package_esp32_index.json
4.Account on WhatsApp
5. Account in Twilio 
6.

## HW Requirements
1.ESP-32 CAM Amazon(shorturl.at/lnpwN)
2.FTDI Programmer (Included in the abvoe link)
3.PIR Sensor for trigger


> Error esp not connecting to WiFi network
> Add this on to the code! 
` #include "soc/soc.h" `
` #include "soc/rtc_cntl_reg.h" `
` WRITE_PERI_REG(RTC_CNTL_BROWN_OUT_REG, 0);  //disable brownout detector `    


