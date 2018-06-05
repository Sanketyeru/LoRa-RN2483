# LoRa-RN2483 communication tutorial
This tutorial is a guide for using RN2483-LoRa module and computer such as ubuntu system or raspberry pi to transmit data over the large range with low power.  In this example, we will transmit time and date using LoRa module and receive it on another LoRa device.

**Following are the steps to implement LoRa communication:**

1. Connect 1st lora device to Raspberry pi 1 (Tx)
2. Connect 2st lora device to Raspberry pi 2 (Rx)
3. Run following command on both raspberry pi devices to check usb port LoRa module connected to 
``` 
ls /dev/ttyUSB*
```
4. Clone the repository by running following command 
```
https://github.com/Sanketyeru/LoRa-RN2483.git
```
5. Install pyserial library on both the pi devices
``` 
pip install pyserial
```
6. Run in terminal loRa_rx.py
```
python loRa_rx.py
```
7. Run in terminal loRa_time_tx.py
```
python loRa_time_tx.py
```
