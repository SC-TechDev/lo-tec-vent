# LoTec Emergency Ventilator Concept - June 6, 2020

This ventilator concept builds on the mechanically actuated Bag-Valve Mask (BVM) designs originally developed at MIT as the [MIT Emergency Ventilator E-Vent](https://e-vent.mit.edu)

The materials provided include engineering drawings, descriptions, photos and videos of designs and proposed production techniques for ventilators Steelcase developed for possible use as part of COVID response actions. Steelcase has not completed the work to validate this design, reviewed these materials with FDA or any other government agency or produced any ventilators. We invite you to use these materials to the extent they are useful in designing and making similar products. However, be advised that these drawings and other materials have not been reviewed by FDA or any other government agency or evaluated for safety or effectiveness for use with any medical condition. We are making these materials available as part of our response to the COVID emergency. Steelcase disclaims any liability for any products made by others using these designs and production techniques. Each user must make their own assessment about the suitability of the design for their particular use.

## Design Goal

The specific goal of this design is to simplify manufacturing and reduce costs and complexity. This is especially relevant in developing countries where servo motors and electronic controls may difficult to procure and maintain. We replaced the servo motor, control board, and electronic user interface with a simple speed-controlled DC motor and adjustable mechanical linkages. This design consists of a standard windshield wiper motor or equivalent connected to a series of mechanical linkages. The steel linkages are assembled with common screws, pins and bearings. The entire unit can be built with standard metal fabrication processes. We improved the user interface with 3D printed handles and covers.

## Proof Of Concept

The following information describes the operation of the ventilator. A prototype was built to prove the concept of the adjustable mechanical linkage. This design is not ready for production or implementation. It does, however, prove that the linkages delivered the desired performance requirements and that the user controls can be simple and intuitive. Further refinement of the design is required to improve durability, manufacturability, and reliability.

![LoTec Vent](Pictures/LoTec%20Vent%20CON2%20Perspective.jpg)

## Basic Function

Two paddles are used to compress the bag, these paddles are geared together to act in concert as was the MIT E-Vent. A six-bar mechanism was developed to drive the paddle movement. The first bar is the rotating lever mounted to the motor. The second bar is the motor push rod. The third bar is the paddle push rod. The fourth bar is the one of the two paddle supports. The fifth bar is a control arm connected to the motor push rod / paddle push rod joint on one end and fixed to ground on the other end (point A – more about how this pivot point is fixed in place later). The sixth bar is the ground plate.

![Oscillating Mechanism](Pictures/Basic%20Function%20-%20Oscillating%20Mechanism.png)

The paddles sweep through a sinusoidal arc as the motor turns. The range of motion, maximum opening angle, and minimum closing angle of the paddles are all controlled by the position of the point A of the control arm.

An automotive windshield wiper motor was used to drive the oscillation. The prototype used a replacement motor for a 1983 Jeep CJ7. PN #REPJ361101. The motor speed was controlled with a pulse width modulated DC speed control module PN CCM5D. Other devices could be used to drive the ventilator. The prototype was noticeably underpowered at slow speeds with this motor and controller so additional work is required to select the appropriate motor, controller and power source.

## Basic Function - User Controls

Two levers are provided for the clinician to adjust the TV and I/E ratio. These levers are part of a 5-bar mechanism that sets the appropriate position for point A. This 5-bar mechanism consists of the two user operated levers, one for TV (1) and one for I/E ratio (2), each pivotally connected to the ground plate (3), and two links (4,5) that determine the position of point A.

![User Controls](Pictures/Basic%20Function%20-%20User%20Controls.png)

The control levers are moved to the desired position by the clinician and locked into place relative to the ground plate. Indicators on the ground plate will display the selected TV or I/E ratio. The control levers can be adjusted while the ventilator is operating and the change in function observed.
The two control levers operate independently. As the TV is adjusted, the I/E ratio will remain unchanged. As the I/E ratio is adjusted, the TV will remain unchanged.

Once the control levers are locked into place, point A is held fixed to the ground plate at the desired location. This position then serves as the pivot point A for the oscillating mechanism determining the range of motion of the ventilator paddles.

A CAD model of the prototype ventilator is provided in this post to clearly show the linkage connections and arrangement of parts to make a functioning unit. The principles of operation described here may be implemented in other ways, potentially further simplifying manufacturability.

## Ventilator Performance

The minimum closing angle of the paddles determines how far the Ambu-Bag is compressed, and the amount of air delivered to the patient (Tidal Volume). The maximum opening angle affects the inhalation / exhalation time ratio (I/E ratio). The user controls previously described determine the range of motion of the paddles. The four pictures below show the user controls at the extremes of adjustment and the associated performance limits of the ventilator. (Notice the position of point A in each of the pictures.)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tidal Volume (TV) between 200ml and 800ml

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I/E ratio between 1 and 3

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Breaths Per Minute (BPM) controlled by the motor speed (rpm)

![Ventilator Performance](Pictures/ventilator%20performance.png)

## Credits

I’d like to thank [Steelcase Inc.](https://www.steelcase.com) for supporting the work to develop and build this ventilator concept. Steelcase’s generous access to the model shop and engineering talent during the early days of the pandemic, when a shortage of ventilators was a mounting concern, was critical to its development. As more firms ramped up production of traditional design ventilators, the team shifted to reduce the technological burden of current designs and focus on purely mechanical solutions. I hope that the Lo Tec Vent is an inspiration to someone to further develop and save lives.

## Engineering Team

Thanks to the following:

Gordy Peterson, Nicholas Krupansky, and Nick Deevers – all Steelcase Engineers

Future Contact: Kurt Heidmann kheidman@steelcase.com
