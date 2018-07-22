## Assembling the `DBV2` {#assembling-dbv2 status=ready}

Point of contact: Redesign Group

Once you have received the parts and soldered the necessary components, it is time to assemble them in a Duckiebot. Here, we provide the assembly instructions for the configuration `DBV2`.

<div class='requirements' markdown="1">

Requires: Duckiebot `DBV2` parts. The acquisition process is explained in [](#acquiring-parts-dbv2).

Requires: having soldered `DBV2` parts. The soldering process is explained in [](#soldering-dbv2).

Requires: Having prepared the power cable. The preparation is explained in [](#power-cable-prep-c0). Note: Not necessary if you intend to build a `DBV2` configuration.

Requires: Time: about 40 minutes.

Results: An assembled Duckiebot in configuration `DBV2`.

</div>

This section is comprised of 11 parts. Each part buils upon some of the previous parts, so make sure to follow them in the following order.

- [Part I: Introduction](#all-pieces)
- [Part II: DC-Motor](#howto-mount-dc)
- [Part III: Rear Wheels](#howto-mount-rear-wheels)
- [Part IV: Steering Mechanism](#howto-mount-steering)
- [Part V: Lower Plate](#howto-mount-base)
- [Part VI: Connecting Plates](#howto-connect-plates)
- [Part VII: Battery](#howto-mount-battery)
- [Part VIII: Deck](#howto-mount-deck)
- [Part IX: Raspberry Pi 3 B+ and MC-Board](#howto-mount-rpi-mc)
- [Part X: LEDs](#howto-install-leds)
- [Part XI: Motors and LEDs connections](#howto-connections)


### Introduction {#all-pieces}

Open the _Tamiya 70112 Buggy Car Chassis_ and take out the components shown in [](#fig:parts_buggy). We will only need these parts out of the set.

<figure id="fig:parts_buggy" figure-caption="Relevant Components in Buggy Set">
     <img src="1_parts_buggy.JPG" style='width:30em'/>
</figure>

<br>
[](#fig:all_parts) shows all parts and components needed to assemble the `DBV2`.

<figure id="fig:all_parts" figure-caption="Components in Duckiebot package.">
     <img src="2_all_parts.JPG" style='width: 30em'/>
</figure>

### DC-Motor {#howto-mount-dc}

In a first step, the dc-motor [](#fig:dc_all) has to be inserted into the driving mechanism. Do not be afraid to press. Once assembled, this component should look like [](#fig:dc_assmbl).


<figure id="fig:dc_all" figure-caption="DC Motor">
     <img src="3_dc_motor_all.JPG" style='width: 30em'/>
</figure>

<br>

<figure id="fig:dc_assmbl" figure-caption="Assembled dc-motor">
     <img src="4_dc_motor_assmbl.JPG" style='width: 30em'/>
</figure>

### Rear Wheels {#howto-mount-rear-wheels}

We now require the pieces shown in [](#fig:dc_wheels) to connect the rear wheels (The bigger ones) to the driving mechanism.

<figure id="fig:dc_wheels" figure-caption="Driving Mechanism: Parts">
     <img src="5_dc_wheels_1.JPG" style='width: 30em'/>
</figure>

<br>
Simply press both wheels towards the inside as in [](#fig:dc_wheels_half).

<figure id="fig:dc_wheels_half" figure-caption="Components in Duckiebot package.">
     <img src="6_dc_wheels_2.JPG" style='width: 30em'/>
</figure>
<br>

The assembled part should look like [](#fig:drive_assmbl).

<br>
</br>

<figure id="fig:drive_assmbl" figure-caption="Assembled Rear Part">
     <img src="7_dc_wheels_3.JPG" style='width: 30em'/>
</figure>

### Steering Mechanism {#howto-mount-steering}

Once the driving mechanism is done, we will now focus on the steering mechanism. All the pieces needed to do this are shown in [](#fig:front_all).

<figure id="fig:front_all" figure-caption="Steering Mechanism: Parts 1">
     <img src="8_front_wheels_1.JPG" style='width: 30em'/>
</figure>

<br>

Put the pieces together as shown in [](#fig:steer_1) and [](#fig:steer_2).

<div>
  <figure id="fig:steer_1" figure-caption="Steering mechanism: Step 1">
      <img src="9_front_wheels_2.JPG" style='width: 10em'/>
  </figure>  
  <figure id="fig:steer_2" figure-caption="Steering mechanism: Step 2">
      <img src="10_front_wheels_3.JPG" style='width: 10em'/>
  </figure>
</div>  
The end result of these two steps should look like [](#fig:steer_3).

<figure id="fig:steer_2" figure-caption="Steering mechanism: Step 3">
     <img src="11_front_wheels_4.JPG" style='width: 30em'/>
</figure>  
Next, we will connect both front wheels to these two pieces. To do so, employ the componenst seen in [](#fig:steer_4) and proceed as depicted next ([](#fig:steer_5), [](#fig:steer_6), [](#fig:steer_7), [](#fig:steer_8), [](#fig:steer_9)).


<figure id="fig:steer_3" figure-caption="Steering Mechanism: Part 2">
     <img src="12_front_wheels_5.JPG" style='width: 30em'/>
</figure>  
<p>
  <center>
    <img src="13_front_wheels_6.JPG" style='width:6em'/>
    <img src="14_front_wheels_7.JPG" style='width:6em'/>
    <img src="15_front_wheels_8.JPG" style='width:6em'/>  

  <center>
    <img src="16_front_wheels_9.JPG" style='width:6em'/>
    <img src="17_front_wheels_10.JPG" style='width:6em'/>
    <img src="18_front_wheels_11.JPG" style='width:6em'/>
  </p>
The assembling of the steering mechanism is concluded if the result looks like [](#fig:steer_end).

<figure id="fig:steer_end" figure-caption="Assembled Steering Mechanism">
     <img src="19_front_wheels_12.JPG" style='width: 30em'/>
</figure>

### Bottom Plate {#howto-mount-base}

<Explain how to connect the servo to this plate, as well as the standoffs>

In this section, you prepare the bottom plate.

Start by taking two nylon screws, three nylon hex nuts the servo motor.  

As indicated in [](#fig:servo_installation), place the servo motor inside the hole in the bottom plate and attach with the two nylon screws.

_Here goes an image showing the servo inside the lower plate._

Keep in mind that you need to add an additional hex nut to the screw located nearer to the front end of the bottom plate to allow for an unhindered rotation.

Secure everything with the nylon hex nuts.  

_Here goes an image showing the servo attached to the lower plate._

Now, take 12 nylon standoffs, make four groups of three and screw them together as shown below:

<p>
<center>
<img src="33_standoffs_1.JPG" style='width:6em'/>
<img src="34_standoffs_2.JPG" style='width:6em'/>
<img src="35_standoffs_3.JPG" style='width:6em'/>
</p>

Introduce them into the bottom plate as shown in [](#fig:standoffs_plate). They will hold the deck.  
Use the Nylon hex nuts to fix the standoffs to the plate.

_This figure needs to be replace by one without the mechanisms connected!_
<figure id="fig:standoffs_plate" figure-caption="Standoffs for bottom plate">
     <img src="37_plate_2.JPG" style='width: 30em'/>
</figure>  


### Connecting Plates {#howto-connect-plates}
With the driving mechanism and the steering mechanism being assembled, and the bottom plate prepared, ([](#fig:lower_plate_parts)), we will now connect these three parts.  

_This is an image of the lower plate and the mechanisms_
<figure id="fig:lower_plate_parts" figure-caption="Lower Plate and Wheels">
     <img src="25_summ.JPG" style='width: 30em'/>
</figure>
<Explain first how to insert the servo motor>  

Begin by connecting the steering mechanism. Connect the plate holding the front wheels to the bottom plate by introducing the rotor into the servo's head ([](#fig:servo_bottom_plate)).  

_Here comes a picture of the driving mechanism and the lower plate._
<figure id="servo_bottom_plate" figure-caption="Connecting Plates: Part 1">
     <img src=".JPG" style='width: 30em'/>
</figure>

To make this connection stable, make sure to use the screw included in the box containing the servo ([](#fig:servo_screw)).

<figure id="fig:steer_3" figure-caption="Steering Mechanism: Part 2">
     <img src="12_front_wheels_5.JPG" style='width: 30em'/>
</figure>  
[](#fig:plate_and_steering) shows the duckiebot up to this point.


<figure id="fig:plate_and_steering" figure-caption="Connected Steering Mechanism">
     <img src="12_front_wheels_5.JPG" style='width: 30em'/>
</figure>  
Proceed now with the rear part of the bot: Connecting the driving mechanism to the lower plate. Use two nylon screws and two hex nuts to attach the dc-motor to the back of the plate as shown in [](#fig:dc_motor_plate).
_One figure showing where to put the screws + better figure here._


<figure id="fig:dc_motor_plate" figure-caption="Connection of dc-motor and lower plate">
     <img src="32_back_2.JPG" style='width: 30em'/>
</figure>

### Battery {#howto-mount-battery}

> Note: This is optional. It is strongly advised, though, since it will make sure the battery stays in its place.

Cut two stripes of one of the velcro roles and stick them to the lower plate ([](#fig:velcro_plate)).

_Here comes an image of the velcro being sticked to the plate_
<figure id="fig:velcro_plate" figure-caption="Velcro on Bottom Plate">
     <img src="" style='width: 30em'/>
</figure>

Cut two stripes of the other velcro role, with the same length, and stick them to the battery ([](#fig:velcro_battery)).

<figure id="fig:velcro_battery" figure-caption="Velcro on Battery">
     <img src="" style='width: 30em'/>
</figure>

Now, simpply press the battery against the plate so that the opposing velcro stripes can stick together([](#fig:battery_plate)).

_Here comes a picture of the battery velcroed to the plate_
<figure id="fig:battery_plate" figure-caption="Installed Battery">
     <img src="" style='width: 30em'/>
</figure>

Now, proceed with the deck.

### Deck {#howto-mount-deck}

Install the assembled camera in the deck with two nylon screws and one nylon hex nut ([](#fig:camera_deck_1)).

_Picture of camera and parts_
<figure id="fig:camera_deck_1" figure-caption="Camera Installation: Parts">
     <img src="" style='width: 30em'/>
</figure>

This procedure is illustrated below:

_Images of camera installation_
<p>
<center>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
</p>

Proceed with the connection of the upper and lower deck: Use 4 nylon screws to attach both plates through the holes indicated in [](#fig:deck_screws).

<figure id="fig:deck:screws">
     <img src="" style='width: 30em'/>
</figure>

Once attached, the bot should look like [](#fig:double_decker).

<figure id="fig:double_decker" figure-caption="Two foor bot">
     <img src="" style='width: 30em'/>
</figure>

### Raspberry Pi 3 B+ and Microcontroller Board {#howto-mount-rpi-mc}

With 8 nylon standoffs and 4 nylon hex nuts, connect the Raspbery Pi and the Microcontroller Board to the upper deck as follows.

First, insert 4 standoffs into the upper deck (The corresponding holes are shown in [](#fig:standoffs_deck)).

<figure id="fig:standoffs_deck" figure-caption="Installed Battery">
     <img src="" style='width: 30em'/>
</figure>


Place the Raspbery Pi's hole on top of the standoffs and fix these components with four additional standoffs.  
Then, insert the microcontrolles board into the Raspberry Pie with the stacking headers.  
The installation is illustrated below.

<p>
<center>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
</p>

### LEDs {#howto-install-leds}

Get the bumpers with the soldered LEDs from [](#soldering-leds) and insert them into the deck.

See below for the illustration of the installation.

<p>
<center>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
</p>

### Batteries, Motors and LEDs connections {#howto-connections}

Everything is built. The only remaining task is to connect both motors and the LEDs to Microcontroller Board and to connect both boars to the battery.

First, connect the women to women jumper wires of the servo motor  to the Microcontroller Board a shown in [](#fig:servo_mc).

<figure id="fig:servo_mc" figure-caption="Servo to Microcontroller">
     <img src="" style='width: 30em'/>
</figure>

Now, connect the women to women jumper wires from the LEDs to the Microcontroller Board as shown in [](#fig:leds_mc).

<figure id="fig:leds_mc" figure-caption="LEDs to Microcontroller">
     <img src="" style='width: 30em'/>
</figure>

Continue by inserting and fixing both male to male jumper wires of the dc motor to the Micrcontroller Board's motor outputs as shown in [](#fig:dc_mc).

<figure id="fig:dc_mc" figure-caption="DC to Microcontroller">
     <img src="" style='width: 30em'/>
</figure>

Lastly, supply both the Raspberry Pi and the Micrcontroller Board with power from the battery. See below for the installation.

<p>
<center>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
<img src="" style='width:6em'/>
</p>
