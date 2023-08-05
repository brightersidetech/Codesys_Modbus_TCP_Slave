# Codesys Modbus TCP Slave Implementation

This is an implemetation of a Modbus TCP Slave in codessys on a PLC. The Slave device is controlled by the Master Device to Read and Write Registers. 

I worked with a TURCK Q300 CDS PLC but can work with any PLC running Codesys V3.5 SP14 patch 2 or later. 

Remember, You will need ```eds Files``` to add a slave device to your device repository. Contact your PLC manufacturer for these files

## Prerequisites
- You may need to install the IODrvModbusTCPSlave Library

## Usage
- The program has been implemented in Codesys V3.5 SP19
- However a Codesys V3.5 SP14 patch 2 has also been saved in this repo. So it will work with any Codesys V3.5 SP14 patch 2 or later
- Just Downlad the ```.project``` files and open as a codesys project

## Demo
- You can find a Video Demo on [how to implement Modbus TCP Slave in Codesys Here](https://www.youtube.com/watch?v=ywS966fEsuo)
