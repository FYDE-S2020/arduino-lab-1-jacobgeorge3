Name: Jacob George

EID:jcg4728

Team Number: 7

## Questions

1. Why does your program need a setup and a loop?

    The setup initializes the hardware and designates what software will be sent to the board. 
A loop sends the software to the hardware on a timed interval so that the hardware continues running forever. 
	
2. What is the downside to putting all your code in a loop?

    It will continue to iterate no matter what. Therefore, it causes difficulty in setting constant values. 

3. Why does your code need to be compiled?

    The compiler breaks down the high level language into information the hardware can understand. 

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    Decreasing the frequency below 100Hz makes the change imperceptible to the human eye, therefore giving it the appearance that the light is getting brighter. 

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    In order for a complete circuit to be made, there must be a loop present. If we did not connect it to ground, the loop would be broken. 

6. What is the difference between synchronous and asynchronous communication?

    Synchronous transmissions are run by an external clock, asynchrous uses specific signals. 

7. Profile of UART: Sent X bytes in Y time 

    16 bytes in 17.5 ms.

8. Profile of SPI: Sent X bytes in Y time

    5 byte in 112 microseconds. 

9. Why is SPI so much faster than UART?

    Since the SPI is synchronous it is able to communicate faster than all other protocols.

10. list one pro and one con of UART

    UART doesn't need a clock to be operated but it is slower speed. 

11. list one pro and one con of SPI

    SPI is the fastest communication but it is more complicated. 

12. list one pro and one con of I2C

    It is more adaptable to different devices but it requires pull-up resistors. 

13. Why does I2C need external resistors to work?

    They need resistors in order to prevent open drain.

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](img/capture.png)

Procedure A, step 4:
![Put path to your image here ->](img/dimmer.png)

Procedure B, UART:
![Put path to your image here ->](img/UARTCapture.png)

Procedure B, SPI:
![Put path to your image here ->](img/SPICapture.png)
