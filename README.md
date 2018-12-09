# PCF8591
This Python code is about a `i2c` -`D/A` &amp;`A/D`- device, `PCF8591` library using `wiring pi` on Rasbperry pi 3. Plese feel free to use !

<p align="center"> 
<img  src="https://github.com/ShuDiamonds/PCF8591/blob/master/image/da%26ad%20example.gif" width="480px"  title="wiring">
</p>
  
## Requirement  
* Raspberry pi 3  
* ubuntu16.04  
* Python 3.x  
* wiring pi  
* [PCF8591](https://www.amazon.co.jp/gp/product/B00BXX4UWC/ref=oh_aui_detailpage_o07_s00?ie=UTF8&psc=1)  
  
<p align="left"> 
<img  src="https://github.com/ShuDiamonds/PCF8591/blob/master/image/pcf8591.jpg" width="120px"  title="FFT-spectrum-analyzer">

## Setting
### i2c enable
1.
```bash
$ sudo raspi-config
```
2. Choose Advanced Option 
3. Enable i2c


## Wiring
### Pin Assign  
PCF8591 --------- Raspberry pi3  
SDA ------------- GPIO2/SDA1  
SCL ------------- GPIO3/SCL1  
VCC ------------- 3.3V  
GND ------------- GND  
 <p align="center"> 
<img  src="https://github.com/ShuDiamonds/PCF8591/blob/master/image/IMG_20180926_112731.jpg" width="480px"  title="wiring">
</p>
 <p align="center"> 
<img  src="https://github.com/ShuDiamonds/PCF8591/blob/master/pin%20assign.png"   title="pin ssign">
</p>


## Usage
### Basic Example
```bash
$ python3 PCF8591.py
```
### `D/A` & `A/D` example
In this program, Raspberry pi read a variable register value(0-255) on `PCF8591` default setting. And 
output to LED(located at lowwer in this picture) which is on PCF8591 using Digital analog converter.
```bash
$ python3 DA&ADexample.py
```
<p align="center"> 
<img  src="https://github.com/ShuDiamonds/PCF8591/blob/master/image/da%26ad%20example.gif" width="480px"  title="Da&ad">
</p>


## Licence

  [MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Related Articles
* [embedded](https://github.com/topics/shu-embedded-systems)
* [Machine Learning data](https://github.com/topics/shu-machine-learning-data)

## Author
  [ShuDiamonds](https://github.com/ShuDiamonds)
