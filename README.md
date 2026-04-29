# 8-Bit Adder-Subtractor with 7-Segment Display

A digital logic circuit built in the **Flastad Circuit Simulator** that performs 8-bit addition and subtraction and visualizes the result on four 7-segment displays.

### 🏗️ Architecture
The project is built from the ground up, beginning with a 2-bit half adder consisting of just basic AND and OR gates. From there, the circuits get more complex, partially consisting of the previously built ones that are integrated in the form of subcircuits, which can be created in Falstad.

The core project is an 8-bit full adder. It is used to add but also to form the tow's complement for subtraction operations. The last task was to display the decimal value with the right sign on four 7-segment displays.
This is achieved through:
* **Binary to BCD Converter**: Converts the 9-bit binary result into 4-bit Binary Coded Decimal (BCD) values for each decimal digit.
* **BCD to 7-segment Decoder**: Decodes the BCD values to properly drive the segments of the displays.

### 🕹️ How to Run
1. Download the '8Bit full adder-subtractor with 7 segment display.txt' file from this repo.
2. Open the [Falstad Circuit Simulator](https://www.falstad.com/circuit/).
3. Got to **File > Import from local file** and select the .txt file.
