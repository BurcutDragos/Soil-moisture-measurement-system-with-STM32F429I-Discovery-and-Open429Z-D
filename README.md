# Soil-moisture-measurement-system-with-STM32F429I-Discovery-and-Open429Z-D
We have implemented an embedded system for monitoring soil moisture using an <b>STM32</b> microcontroller. The system code reads an analog signal from a soil moisture sensor, interprets its value to determine the soil moisture level, and sends the results via <b>UART</b> to a terminal application (in our case, <b>Tera Term</b>). A digital <b>GPIO</b> pin is also monitored to provide a binary indication of soil conditions.

## Software tools used:
* Programming Language: C
* STM32CubeMX
* Keil uVision5
* Tera Term

## Hardware components used:
* STM32F429I Discovery + Open429Z-D development kit
* soil moisture sensor
* PCB circuit with comparator/converter
* six female-female connection wires
* USB power cable with circular plug
* two USB A – USB mini B cables

## Installation:
<b>1. Clone the Repository:</b>
git clone https://github.com/BurcutDragos/Soil-moisture-measurement-system-with-STM32F429I-Discovery-and-Open429Z-D.git

<b>2. Navigate to the Project Directory:</b>
cd Soil-moisture-measurement-system-with-STM32F429I-Discovery-and-Open429Z-D

## Running the Application:
Run the application in Keil uVision5.

## Contributing:
1. Fork the repository.
2. Create a new branch: <b>git checkout -b my-feature-branch</b>
3. Make your changes and commit them: <b>git commit -m 'Add some feature'</b>
4. Push to the branch: <b>git push origin my-feature-branch</b>
5. Submit a pull request.

## License:
This project is licensed under the GPL-3.0 License - see the LICENSE file for details.

## Authors: 
Burcut Ioan Dragos, Burcut Vasile Cezar.
