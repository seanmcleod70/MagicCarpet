# Magic Carpet - Flight Control Laws using Direct Lift

The F/A-18E/F/G aircraft and the F-35 have specific flight control laws for carrier approach and landing which
makes use of direct lift to make the approach and landing task easier for the pilot. 

The aim of this repo is to implement the equivalent flight control laws in a JSBSim model.

## Papers

[The Control Characteristics of Aircraft Employing Direct-Lift Control](Papers/The%20Control%20Characteristics%20of%20Aircraft%20Employing%20Direct-Lift%20Control.pdf)

The theory is developed for the control characteristics of aircraft in which direct lift is commanded
directly by the pilots' stick. Basic requirements are established for acceptable response characteristics; of
particular importance is the location at which direct lift acts relative to the centre of gravity, the aerodynamic
centre, and manoeuvre point. The affective line of action of the control lift can be controlled by
mechanical interconnections between the conventional pitch control and direct-lift systems. Potential
benefits of direct-lift control include improved precision in landing large aircraft, more effective control
of gust effects, and reduced possibility of stalling.

[Direct Lift Control: A review of its principles, merits, current and future implementations](Papers/Direct%20Lift%20Control%20-%20A%20review%20of%20its%20principles%20merits%20current%20and%20future%20implementations.pdf)

Direct Lift Control (DLC) is the capability to directly and intentionally influence lift on a fixed-wing aircraft
by means of aerodynamic control devices, with minimum change of its angle of attack. Although several
definitions exist, with various degrees of ambiguity, the combination of DLC and pitch attitude control has
unambiguously proven to reduce pilot workload and improve flying comfort considerably. DLC has historically
seen several applications on so-called inflight simulators and, recently, this capability has been rolled out over
several aircraft types of the US Navy fleet, massively reducing pilot workload during carrier landings. On the
civil front, only one aircraft type has been equipped with this capability, despite its very positive reception
by flight crews and passengers. The intention of this paper is to revive interest in civil DLC applications, by
reviewing in-depth its basic principles, characteristic features, benefits, and implementations so far. Several
modern aircraft and disruptive wing configurations appear to be inherently capable of accommodating DLC
functionality from a flight physical, systems, and software point of view. The proven benefits of DLC are likely
to well outweigh the cost of the added functionality.

[Project MAGIC CARPET: Advanced Controls and Displays for Precision Carrier Landings](Papers/Project%20Magic%20Carpet%20-%20Advanced%20Controls%20and%20Displays%20for%20Precision%20Carrier%20Landings.pdf)

Maritime augmented guidance with integrated controls for carrier approach and 
recovery precision enabling technologies (MAGIC CARPET) is an enhanced set of flight 
control laws and Head-Up Display symbology for F/A-18E/F/G aircraft which seek to reduce 
the unique pilotage skills required for shipboard landings. Integrated Direct Lift Control 
significantly simplifies ‘ball flying’ by allowing for repeatable and precise flightpath changes 
using lift as directly commanded via longitudinal stick displacements. Additionally, ‘Delta 
Path’ control mode adds a feature that allows the aircraft to capture, maintain, and return 
to the 'ideal' 3.5 degree glideslope, nearly hands off. This essentially de-couples the 
glideslope task from the lineup task. The enhanced HUD symbology provides much 
improved direct pilot feedback cues on the magnitude of glideslope and lineup corrections. 
Recent shipboard flight test completed aboard the USS Bush (CVN-77) in April 2015 
confirmed a 50% reduction in touchdown dispersion as well as greatly reducing overall 
carrier approach workload as observed through real-time pilot feedback. Test results, pilot 
comments and lessons learned will be presented. 


