# Arduino LCD Display Example

This project demonstrates how to use a LiquidCrystal I2C display with an Arduino. The display will show two different messages, one after the other, with a delay in between.

## Components

- Arduino board (e.g., Arduino Uno)
- LCD with I2C interface
- Connecting wires

## Circuit Diagram

- Connect the SDA pin of the LCD to the A4 pin on the Arduino (SDA).
- Connect the SCL pin of the LCD to the A5 pin on the Arduino (SCL).
- Connect the VCC and GND pins of the LCD to the Arduino's 5V and GND, respectively.

## How to Use

1. **Upload the Code**: Upload the provided code to your Arduino board.
2. **Assemble the Circuit**: Connect the LCD to the Arduino according to the circuit diagram.
3. **Power the Arduino**: Ensure the Arduino is powered on and connected to your computer or a power source.
4. **Observe the Display**: The LCD will show "Hello World" and "KSK LV. 4" alternately, with each message displayed for two seconds.

## Troubleshooting

- **No Display**: Ensure that the LCD is properly connected and powered. Check the contrast potentiometer on the LCD if available.
- **Incorrect Display**: Verify that the I2C address `0x27` is correct for your LCD. You might need to use an I2C scanner sketch to determine the correct address.
- **Libraries**: Ensure you have the `LiquidCrystal_I2C` library installed in your Arduino IDE. If not, install it through the Library Manager.

## Maintainer

[Sandi Andrian](mailto:andrian.sandi@gmail.com)

## License

This project is licensed under the MIT License.
