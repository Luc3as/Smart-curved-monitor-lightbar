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

* [Wemos D1 Mini](https://www.aliexpress.com/item/32831353752.html?spm=a2g0o.productlist.0.0.153f1669auHDVy&algo_pvid=d2e52dc5-09a3-4128-b33f-f8edf82bf099&algo_exp_id=d2e52dc5-09a3-4128-b33f-f8edf82bf099-0&pdp_ext_f=%7B%22sku_id%22%3A%2210000014440741148%22%7D&pdp_npi=2%40dis%21EUR%211.95%211.95%21%21%21%21%21%402100bddf16695713523975448ec69b%2110000014440741148%21sea&curPageLogUid=wjcIQQBQWYzf)
* [USB-C female connector ](https://www.aliexpress.com/item/1005002795893679.html?spm=a2g0o.order_list.0.0.18751802bFIGnc)
* [Hot melt inserts ](https://www.aliexpress.com/item/1005003150553284.html?spm=a2g0o.order_list.0.0.18751802bFIGnc)
* [Dual CCT 5V LED Strip](https://www.aliexpress.com/item/1005001729120581.html?spm=a2g0o.order_list.0.0.18751802bFIGnc)
* [WS2812b RGB LED Strip](https://www.aliexpress.com/item/1005002890783311.html?spm=a2g0o.productlist.0.0.249574carP6i8E&algo_pvid=4a2dd48e-3c8f-4be8-9fe9-4513ba24b418&algo_exp_id=4a2dd48e-3c8f-4be8-9fe9-4513ba24b418-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000029156336140%22%7D&pdp_npi=2%40dis%21EUR%2134.26%2119.53%21%21%21%21%21%402100bdd016695714637331031e42ef%2112000029156336140%21sea&curPageLogUid=qV0vPj5TmLlr)
* [IRFZ44N MOSFET Transistor](https://www.aliexpress.com/item/1005004930806422.html?spm=a2g0o.productlist.0.0.35c428daaSC1gC&algo_pvid=b536e603-06af-44a7-baf1-a7388cabf138&algo_exp_id=b536e603-06af-44a7-baf1-a7388cabf138-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000031067190205%22%7D&pdp_npi=2%40dis%21EUR%210.95%210.47%21%21%21%21%21%402100bdd016695715236882195e42ef%2112000031067190205%21sea&curPageLogUid=dfzz1Zigxw7S)


## If you liked my work, you could buy me a coffee :)

<a class="" target="_blank" href="https://www.buymeacoffee.com/luc3as"><img src="https://lukasporubcan.sk/images/buymeacoffee.png" alt="Buy Me A Coffee" style="max-width: 217px !important;"></a>

### Or send some crypto

<a class="" target="_blank" href="https://lukasporubcan.sk/donate"><img src="https://lukasporubcan.sk/images/donatebitcoin.png" alt="Donate Bitcoin" style="max-width: 217px !important;"></a>	
				    			    			    							    			     			    	