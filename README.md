# balloon
This Repository will have the code for Raspberry or Orange Pi for Balloon<br>
This project has the code for the Baloon telemetry system used in Bacar5<br>
This code generate a CW and GPS APRS telemetry on the 2m Band using Giga Technology SDR transmitter board.<br>
The Raspberry Pi hat TX board detaiils is avalible here http://www.giga.co.za/ocart/index.php?route=product/product&path=59_82&product_id=296<br> 
This system can also be used for a fm Repeater on the baloon<br>
<b>How dose it work?</b><br>
The Application is using direwalf, cw, gpsd, rpitx to create the APRS and CW message. If you add rtl dongell you can cortole the system as well.<br> 
<b>What Applications do you need to install for telemetry to worK?</b><br>
1) Install direwalf<br>
2) Install cw<br>
3) Install alsa loopback<br>
4) Install gpsd<br>
5) Install sox<br>
6) Install rpitxi<br>
<b>What harware do you need for this project</b><br>
1) Raspberry Pi 2 - 3 use the A  as it use less poer from Giga Terchnology<br>
2) RTL dongle if you want to controle the Pi reomtely via APRS from Giga Technology <br>
3) Battery pack and managemen system From Giga Technology <br>
4) USB GPS from Giga Technology<br>
5) SDR Raspberry Pi transmitter hat from Giga Technology<br>
6) Rubber duck Antenna for Hat and one for Rtl dongle.<br>
7) Temprature sensor.<br>
