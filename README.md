Welcome to the Delay Board project! This innovative delay board is designed to assign individual delays to respective channels, enabling precise control over timing in various applications. Controlled via Arduino and a Python script, this modern board features Wi-Fi and Bluetooth connectivity, making it ideal for remote monitoring and management.
Key Features
Individual Delay Control: Easily set unique delay times for each channel, allowing for customized performance based on your specific requirements.

Arduino Compatibility: Harness the power of Arduino for seamless integration and programming, enabling you to develop and deploy your projects quickly and efficiently.

LE_PIN number should be changed according to how defined in the schematic of Anubis_Delay_Board.
CLK and DATA are common to all 8 chips.

The initial delay value can be changed using;
int delayValue[8] = {,,,,,,,}

Currently: (as mentioned in the schematic)

CHIP PIN - ARDUINO PIN NUMBER

LE_1 - 22
LE_1 - 24
LE_1 - 26
LE_1 - 28
LE_1 - 30
LE_1 - 32
LE_1 - 34
LE_1 - 36

CLK - 44
DATA - 46

Python Script Control: Utilize Python scripts to control the delay board, offering flexibility in automation and enhancing user experience with programmable functionality.

Wi-Fi and Bluetooth Connectivity: Stay connected! With built-in Wi-Fi and Bluetooth capabilities, you can monitor and manage your delay board from anywhere, making it suitable for both home and industrial applications.

TTL (Transistor-Transistor Logic) and NIM (Network Interface Module) Output Options: The delay board can output signals in either TTL or NIM mode.

TTL: A standard logic level used in digital circuits, allowing for reliable communication between components with minimal power consumption.
NIM: A communication protocol that facilitates the integration of networked devices, ensuring efficient data transfer and system interoperability.
Importance of the Delay Board
The Delay Board is an essential tool for various applications, including audio processing, lighting control, and automation systems. By enabling precise control over timing, it allows users to synchronize multiple channels effectively, enhancing the overall performance of complex systems. The added connectivity features also provide flexibility for remote operation, making it a versatile choice for both hobbyists and professionals.
