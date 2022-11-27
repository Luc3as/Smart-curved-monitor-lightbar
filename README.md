<img src="./Photos/titulka.jpg" width="700">

## Idea behind this project

Custom made light bar, with easy connectivity and controllability from any home automation system. 
Integrated dual CCT light strip, to set just right color of light by time of day or type of task doing under the light. 
Backlight providing custom non disruptive mood light, with advanced effects possible thanks to individually addressable light strip. 
Everything powered from single USB-C 5V connector.

Universal attachment arms with adjustable height and angle for different monitor types.




## Designing the lightbar
Main goal here was to find a way and arrangement of led strip to provide light shining to desk, but without glaring into users’ eyes sitting behind the desk or casting light glares on monitor. I did some tests, measurements, came up with different lamp body designs, after few versions I came up with good solutions to satisfy those needs.  
<img src="./Photos/design1.jpeg" width="400">
<img src="./Photos/design2.jpeg" width="400">
<img src="./Photos/design3.jpeg" width="400">
<img src="./Photos/design4.jpeg" width="400">

## Printing and assembling

As material I picked PETG, but PLA would be OK too.

<img src="./Photos/assembly1.jpeg" width="400">

Parts was designed to fit on standard size 3D printer

<img src="./Photos/assembly2.jpeg" width="400">

Parts which will hold some mechanical load was designed for mechanical 3D inserts. 

<img src="./Photos/assembly3.jpeg" width="400">

## LEDs and electronics

I used dual CCT light strip powered by 5V, and WS2812b LED strip for backlight. Electronics is very simplistic, main controller is Wemos D1 mini, and 5V USB-C female connector board. There is no physical button for controlling the light as I will use home automation to control it. However, there are free pins on ESP8266 so some buttons or motion sensors could be easily installed in covers. 
To drive 2 white channels of LEDs I used simple connection of 2 N-Mosfet transistors to the outputs of ESP8266. Data pin of RGB led strip was connected right to the ESP8266. 


<img src="./Photos/electronics1.jpeg" width="400">
<img src="./Photos/electronics2.jpeg" width="400">
<img src="./Photos/electronics3.jpeg" width="400">

## Firmware 

For firmware I used ESPHOME, you can find config in firmware.yaml

## Final installation

<img src="./Photos/final1.jpeg" width="400">
<img src="./Photos/final2.jpeg" width="400">
<img src="./Photos/final3.jpeg" width="400">
<img src="./Photos/final4.jpeg" width="400">
<img src="./Photos/final5.jpeg" width="400">
<img src="./Photos/final6.jpg" width="400">
<img src="./Photos/final7.jpg" width="400">

## Materials

TBD

## If you liked my work, you could buy me a coffee :)

<a class="" target="_blank" href="https://www.buymeacoffee.com/luc3as"><img src="https://lukasporubcan.sk/images/buymeacoffee.png" alt="Buy Me A Coffee" style="max-width: 217px !important;"></a>

### Or send some crypto

<a class="" target="_blank" href="https://lukasporubcan.sk/donate"><img src="https://lukasporubcan.sk/images/donatebitcoin.png" alt="Donate Bitcoin" style="max-width: 217px !important;"></a>	
				    			    			    							    			     			    	