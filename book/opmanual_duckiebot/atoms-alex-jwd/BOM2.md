## Bill of Materials for DBV2 {#acquiring-parts-dbv2 status=ready}

The trip begins with acquiring the parts. Here, we provide a link to all bits and pieces that are needed to build a Duckiebot, along with their price tag. If you are wondering what is the difference between different Duckiebot configurations, read [this](#duckiebot-configurations).

In general, keep in mind that:

- The links might expire, or the prices might vary.
- Shipping times and fees vary, and are not included in the prices shown below.
- Substitutions are OK for the mechanical components,
  and not OK for all the electronics, unless you are OK in writing
  some software.
- Buying the parts for more than one Duckiebot makes each one cheaper than buying only one.
- For some components, the links we provide contain more bits than actually needed.

<div class='requirements' markdown="1">

Requires: Cost: USD 150 + Shipping Fees   

Requires: Time: 15 days (average shipping for cheapest choice of components)  

Results: A kit of parts ready to be assembled in a `DBV2` configuration.  

Next steps: After receiving these components, you are ready to do some [soldering](#soldering-boards-c0) before [assembling](#assembling-duckiebot-db17-ttic) your `DBV2` Duckiebot.

</div>




## Materials
| Part   | Price          |
| :----- | :-------------  |
|[Chassis](https://www.amazon.com/Tamiya-70112-Buggy-Car-Chassis/dp/B002DR3H62/ref=br_lf_m_7x64hsptfvee7uz_img?_encoding=UTF8&s=toys-and-games)     |  USD 20.94     |
|Chassis - Laser Cut | Ask JT |
|[Camera with 160-FOV Fisheye Lens](https://tinyurl.com/ybwrcywc) |USD 22|
|[Camera Mount](https://tinyurl.com/ybyewdrt)|                        USD 8.50|  
|[300mm Camera Cable](https://www.adafruit.com/product/1648) |USD 2 |
|[Raspberry Pi 3 - Model B+](https://tinyurl.com/ycsujzb9) |USD 35 |
|[Power supply for Raspberry Pi](https://www.adafruit.com/product/1995)|USD 7.50 |
|Microcontroller Board | Ask JT |
|[Servo Motor](https://www.pololu.com/product/1051) |USD 9.95 |
| [Heat Sinks](https://tinyurl.com/yanradnp) |USD 2.90 |     
|[16 GB Class 10 MicroSD Card](https://tinyurl.com/ydawrgdx) |USD 10 |
|[Mirco SD card reader](https://www.adafruit.com/product/939 ) |USD 6 |
|[Battery](https://www.amazon.com/dp/B01K702S66/ref=emc_b_5_t)  |USD 25.99 |
|[USB to microUSB](https://www.amazon.com/CableCreation-Triple-Shielded-Charger-Android/dp/B013G4EAEI/ref=sr_1_20?s=electronics&ie=UTF8&qid=1532016619&sr=1-20&keywords=usb+to+micro+usb+cable) |USD 4.99 |
|[22 Nylon Standoffs (M2.5 12mm F 6mm M)](https://tinyurl.com/y9uy73b2) |USD 0.05/piece |
|[18 Nylon Hex Nuts (M2.5)](https://tinyurl.com/ydy4znem)|USD 0.02/piece|
|[10 Nylon Screws (M2.5x10)](https://tinyurl.com/ya2uo9so)|USD 0.05/piece|
|Special Screws |Ask Mac/Michi |
|[Joypad](https://tinyurl.com/y9klooef)|USD 10.50|
|[Addressable LEDs](https://www.adafruit.com/product/1734) |USD 4.95 |
|[2 Male to Male Jumper Wires](https://www.amazon.es/daorier-Multicolor-40-pines-protoboard-Male-Male/dp/B072554P66/ref=sr_1_7?ie=UTF8&qid=1532018102&sr=8-7&keywords=jumper+wire+male+male) |USD 1 |
|[2 Servo Wires](https://www.amazon.com/RCmall-Servo-Extension-Cable-Futaba/dp/B01MQPCLPT/ref=sr_1_3?ie=UTF8&qid=1532018556&sr=8-3&keywords=servo+wires)|USD 6.99 |


Total for `DBV2` Configuration: USD 181.17

### Chassis

We selected the _Tamiya 70112 Buggy Car Chassis_ [](#fig:chassis) due to its car-like dynamics and size.

We will only use some components included in the set since bigger, laser-cutted plates more suited to hold all the necessary parts will substitute the wooden platform included in the set.

<div figure-id="fig:chassis" figure-caption="Tamiya 70112 Buggy Car Chassis Set">
     <img src="Buggy_Car_DBV2" style='width: 15em'/>
</div>


### Chassis - Laser Cut

Download this [pdf]() and let it be laser cutted.
One possible place to let this be done can be found [here]().

### Camera

The Camera [](#fig:camera) is the main sensor of the Duckiebot. All versions equip a 5 Mega Pixels 1080p camera with wide field of view fisheye lens.

<div figure-id="fig:camera" figure-caption="Camera with 160-FOV Fisheye Lens">
     <img src="camera.PNG" style='width: 15em'/>
</div>


### Camera Mount

The camera mount [](#fig:cameramount) serves to keep the camera looking forward at the right angle to the road (looking slightly down). The front cover is not essential.

<div figure-id="fig:cameramount" figure-caption="Camera Mount">
     <img src="camera_holder.PNG" style='width: 15em'/>
</div>

<br>
The assembled camera (without camera cable) is shown in [](#fig:ass_cam):
</br>

<div figure-id="fig:ass_cam" figure-caption="Assembled Camera">
     <img src="assembled_camera.PNG" style='width: 15em'/>
</div>


### 300mm Camera Cable

A longer (300 mm) camera cable [](#fig:cam_cable) makes assembling the Duckiebot easier, allowing for more freedom in the relative positioning of camera and computational stack.

<div figure-id="fig:cam_cable" figure-caption="300mm Camera Cable">
     <img src="300mm_ccable.PNG" style='width: 15em'/>
</div>

### Raspberry Pie 3 - Model B+

The Raspberry Pie is the central computer of the Duckiebot. Duckiebots use Model B+ [](#fig:rpi) (1.4GHz 64-bit quad-core processor), a small but powerful computer.

<div figure-id="fig:rpi" figure-caption="Raspberry Pi 3 B+">
     <img src="RPi_3B+.jpg" style='width: 15em'/>
</div>

### Power supply for Raspberry Pi

We want a hard-wired power source (5VDC, 2.4A, Micro USB) to supply the Raspberry Pi while not driving. This charger [](#fig:power_supply) can double down as battery charger as well.

<div figure-id="fig:power_supply" figure-caption="Power Supply">
     <img src="power_supply.PNG" style='width: 15em'/>
</div>


### Microcontroller Board



### Servo Motor

The Servo Motor [](#fig:servo_motor) is responsible for the steering mechanism to move. With a stall torque of 18-21 oz-in, this small motor has enough power to make the duckiebot turn even on the spot.

<div figure-id="fig:servo_motor" figure-caption="Servo Motor">
     <img src="servo_motor.png" style='width: 15em'/>
</div>


### Heat Sinks

The Raspberry Pi will heat up significantly during use. It is warmly recommended to add heat sinks [](#fig:heat_sinks_sinks). Since we will be stacking HATs on top of the Raspberry Pi with 15 mm standoffs, the maximum height of the heat sinks should be well below 15 mm. The chip dimensions are 15x15mm and 10x10mm.

<div figure-id="fig:heat_sinks" figure-caption="H">
     <img src="heat_sinks.jpg" style='width: 15em'/>
</div>


### 16 GB Class 10 MicroSD Card

The MicroSD card [](#fig:sd_card) is the hard disk of the Raspberry Pi. 16 GB of capacity are sufficient for the system image.

<div figure-id="fig:sd_card" figure-caption="Micro SD card">
     <img src="sdcard.PNG" style='width: 15em'/>
</div>


### Micro SD card reader

A microSD card reader [](#fig:sd_card_reader) is useful to copy the system image to a Duckiebot from a computer to the Raspberry Pi microSD card, when the computer does not have a native SD card slot.

<div figure-id="fig:sd_card_reader" figure-caption="SD Card Reader">
     <img src="sdcard_reader.PNG" style='width: 15em'/>
</div>


### Battery

The battery [](#fig:battery) provides power to the Duckiebot.

We choose this battery because it has a good combination of size (to fit in the lower deck of the Magician Chassis), high output amperage (3A per port at 5V DC) over two USB outputs, an okay capacity (5000 mAh) at an affordable price. The battery linked in the table above comes with one USB to microUSB cables, so another one is needed.

<div figure-id="fig:battery" figure-caption="Battery">
     <img src="battery.jpg" style='width: 15em'/>
</div>


### USB to microUSB

One USB to microUSB cable [](#fig:usb_microusb) to connect the battery to the Microcontroller Board.

<div figure-id="fig:usb_microusb" figure-caption="USB to microUSB cable">
     <img src="usb2microusb.jpg" style='width: 15em'/>
</div>


### Nylon components

We use non electrically conductive standoffs (M2.5 12mm F 6mm M), nuts (M2.5), and screws (M2.5x10mm)
[](#fig:nylon_comps) to hold the Raspberry Pi to the chassis and the HATs stacked on top of the Raspberry Pi.

The Duckiebot requires 22 standoffs, 18 Nuts and 10 screws.

<div figure-id="fig:nylon_comps" figure-caption="Nylon components">
     <img src="mech-bits.jpg" style='width: 15em'/>
</div>

### Joypad

The joypad [](#fig:joy_pad) is used to manually remote control the Duckiebot. Any 2.4 GHz wireless controller (with a _tiny_ USB dongle) will do.

The model linked in the table does not include batteries.

<div figure-id="fig:joy_pad" figure-caption="Joypad">
     <img src="joystick.png" style='width: 15em'/>
</div>



<br>
Requires: 2 AA 1.5V batteries [](#fig:aa_batteries)
</br>


<div figure-id="fig:aa_batteries" figure-caption="AA 1.5V Batteries">
     <img src="batteries_joystick.PNG" style='width: 15em'/>
</div>



### Addressable LEDs

These adressable LEDs [](#fig:addr_leds) have been selected due to their size and suitable brightness.

<div figure-id="fig:addr_leds" figure-caption="Addressable LEDs">
     <img src="addr_leds.jpg" style='width: 15em'/>
</div>


### Male to Male Jumper Wire

2 male-male jumper wires [](#fig:m2m_wires) are needed to connect the Microcontroller Board to the DC-Motor.

<div figure-id="fig:m2m_wires" figure-caption="Male to Male Jumper Wires">
     <img src="jumper_wires.jpg" style='width: 15em'/>
</div>


### Servo Wire

2 Servo Wires [](#fig:servo_wire) are needed to connect the servo motor and the LEDs to the Microcontroller Board.

<div figure-id="fig:servo_wire" figure-caption="Servo Wire">
     <img src="servo_wire.jpg" style='width: 15em'/>
</div>
