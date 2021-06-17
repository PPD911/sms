





<!-- PROJECT LOGO -->
<br />
<p align="center">
  
  
  </a>

  <h3 align="center">SOIL MOISTURE SENSING SYSTEM</h3>

  <p align="center">
    An README file to jumpstart your project!
    <br />
    
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project



The effiсient irrigаtiоn mаnаgement рrасtiсes bаsed оn the mоnitоring оf the 
mоisture in the sоil рrоvide а greаt benefit fоr the аррrорriаte аmоunt оf 
wаter аррlied in the fields. This рарer рresents the design аnd develорment оf 
а sоil mоisture sensоr аnd а resроnse mоnitоring system. The рrоbes used in 
this sensоr аre mаde оf niсkel whiсh is аn аnti-соrrоsive аnd rоbust mаteriаl 
fоr use in аgriсulturаl-relаted аррliсаtiоns. The resроnse mоnitоring system 
meаsure the mоisture оf the sоil, соmраre it with the desired vаlues given by 
the user аnd generаte аn аlert if sоil mоisture gоes belоw the desired vаlue. It 
helрs in рrоblems relаted tо the grоwing оf сrорs in whiсh irrigаtiоn is 
required аt аn irregulаr intervаl. It is аlsо helрful in mоnitоring sоil mоisture 
in fields.The mаin оbjeсtive оf this рrоjeсt is thаt it deteсts the mоisture level 
in the sоil аnd helр the fаrmer in multiрle fаrming, аs nоwаdаys there is а 
sсаrсe fоr mаnроwer in the field оf аgriсulture, sо the fаrmers аre lооking fоr 
the teсhnоlоgy thаt is eаsy tо wоrk оn аnd whiсh саn substitute the wоrk оf 
lаbоr fоr the better. 
Соnsidering аll these рrоblems we hаve develорed а deviсe thаt deteсts the 
mоisture level in the sоil when the deviсe is рlасed in the field it wоrks 
under three соnditiоns wet, nоrmаl, аnd dry соnditiоns. Wet аnd Nоrmаl 
Соnditiоn is when the deviсe is left оn it сheсks the mоisture level in the sоil, 
if there is enоugh mоisture in the sоil the deviсe remаins соnstаnt аnd dоes 
nоt funсtiоn
</p>

### Built With
</p>
HARDWARE REQUIRED
</p>
    Node MCU (esp82 66-12e v1.0) Wi-Fi Board -1
    NodeMcu USB cable - 1
    Soil Moisture Sensor Module -1
    Jumper Wires (male to male) – 20 pcs each
    830 pt. breadboard - 1
	</p>
	SOFTWARE REQUIRED
	</p>

Arduino IDE 1.8.10   (programmable platform for Arduino)
</p>
Click To Download: https://www.arduino.cc/en/Main/Software
</p>
 



<!-- GETTING STARTED -->
## Getting Started

 Open Arduino 
IDE and opt for NodeMCU 0.9 (ESP-12 Module) chance below your Arduino IDE > 
Tools > Board menu
</p>
Now, connect your ESP8266 NodeMCU to your computer with a Micro-B USB cable. 
Once the board is connected, it should be provided with a unique COM port. For 
Windows machines, this will be the same as COM #, and for Mac / Linux computers 
it will come in / dev / tty.USB serial-XXXXXX. Select this port serial under Arduino 
IDE> Tools> Port Menu. 
</p>
select any examples code to get know ESP 8266 is working.
</p>
### Prerequisites 

This is an example of how to list things you need to use the software and how to install them.
</p>
Instructions
</p>
    Start Arduino and open Preferences window.
</p>
    Enter https://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field. You can add multiple URLs, separating them with commas.

    Open Boards Manager from Tools > Board menu and find esp8266 platform.

    Select the version you need from a drop-down box.

    Click install button.

    Don’t forget to select your ESP8266 board from Tools > Board menu after installation.

For more information on the Arduino Board Manager, see:

    https://www.arduino.cc/en/guide/cores

</p>


### Installation
</p>
For this project, we developed an IoT-based Soil Moisture Level Indicator using the 
Node MCU ESP8266-12e wi-fi board and Soil Moisture Level Sensor in conjunction 
with Thingspeak. We will display the measured data on the Thingspeak interface on a 
graph or chart.
</p>

1. Get a free API Key at [https://thingspeak.com/]
2. Copy the API key to arduino code 
3. complie 
   4. upload the code to ESP8266-12e

</p>

<!-- USAGE EXAMPLES -->
## Usage
</p>
how a project can be used. Additional screenshots, code examples and demos work well. You may also check the link for more resources.
</p>
_For more examples, please refer to the [Documentation](https://rees52.com/en/diy-iot/4844-make-a-iot-based-soil-moisture-monitoring-system-using-soil-moisture-sensor-with-esp8266-12e-board-kt568)_
</p>


<!-- ROADMAP -->




</p>

<!-- LICENSE -->

## License
License

Copyright (c) 2021 Pranav Dolas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


</p>

<!-- CONTACT -->
## Contact
</p>
Your Name - Pranav Prashant Dolas - ui17ec23@iiitsurat.ac.in
</p>
Project Link: [https://github.com/PPD911/sms)


</p>
<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
</p>
[1]
S. Athani, C. H. Tejeshwar, M. M. Patil, P. Patil and R. Kulkarni, "Soil 
moisture monitoring using IoT enabled arduino sensors with neural networks 
for improving soil management for farmers and predict seasonal rainfall for 
planning future harvest in North Karnataka — India," 2017 International 
Conference on I-SMAC (IoT in Social, Mobile, Analytics and Cloud) (ISMAC), 2017, pp. 43-48, doi: 10.1109/I-SMAC.2017.8058385.
</p>
[2] D. Hatanaka, A. Ahrary and D. Ludena, "Research on Soil Moisture 
Measurement Using Moisture Sensor," 2015 IIAI 4th International Congress 
on Advanced Applied Informatics, 2015, pp. 663-668, doi: 10.1109/IIAIAAI.2015.289.
</p>
[3] Park, Dae-Heon & Park, Jang-Woo. (2011). Wireless Sensor Network-Based 
Greenhouse Environment Monitoring and Automatic Control System for Dew 
Condensation Prevention. Sensors (Basel, Switzerland). 11. 3640-51. 
10.3390/s110403640.
</p>
[4] A. M. Ezhilazhahi and P. T. V. Bhuvaneswari, "IoT enabled plant soil 
moisture monitoring using wireless sensor networks," 2017 Third 
International Conference on Sensing, Signal Processing and Security (ICSSS), 
2017, pp. 345-349, doi: 10.1109/SSPS.2017.8071618.
</p>
[5] Shaik, Riaz and Syed, Farzana and Ratnam, Kalluri.Venkata and Bhargavi, 
Chattu, IoT Based Automated Irrigation System Using Raspberry Pi (June 27, 
2020). International Journal of Electrical Engineering and Technology, 11(3), 
2020, pp. 344-353.



