# STM32 ADC App
This application employs an Analog-to-Digital Converter (ADC) to periodically sample data from a potentiometer. Every 300 milliseconds, the ADC converts the analog voltage signal from the potentiometer into a digital value.

To ensure data integrity, the application includes a timeout mechanism. If the ADC fails to complete a conversion within one second, it aborts the current attempt and initiates a new conversion.


## ADC configuration
![image](https://github.com/user-attachments/assets/93a4b37c-e295-4ec2-a5e1-8475787170f5)

## Clock Configuration
We are using APB2 peripheral clock which is 84 MHZ
![image](https://github.com/user-attachments/assets/357f2f08-876d-4c91-b19d-ac8d99c84ba0)

## Hardware connection set up
![image](https://github.com/user-attachments/assets/64962dea-a1b0-4177-bbe5-faf81dae8a69)

## Reading data from potentiometer 
![image](https://github.com/user-attachments/assets/9946ec63-ada1-4609-9205-faf00e0182ec)

Microcontroller STM32F4VE

Course name: Mastering STM32 microcontrollers

Link: https://www.udemy.com/course/mastering-stm32f407-microcontrollers/
