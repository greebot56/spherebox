# Spherebox <img src="./data/Sphere.png" width=64 height=64 alt="Geometry" />
### Gear-up for a new concept in mechanical power transmission for renewable energy
#### *Note: This page as it stands represents an MVP for sharing - significant upgrades are planned!*

Spherebox is the working title of a mechanism to efficiently gear-up (or down) rotary motion at ratios of 20:1 or more in a single stage, using spherical geometry and magnets.

I believe it is "novel" in the sense of an invention, but I want to "open-source it" and share it with the world rather than go through the patent process.  Partly, because if it turns out to be genuinely useful, I don't think it should be locked behind a patent.  And, if having it "community owned" will help populaise it, so much the better

Potential Benefits:
* No sliding contact - less friction, less wear --> Less maintainance **+ less power loss?**
* "Soft" backlash, from magnetic force transmission:
  * No risk of impact-loading gear teeth if the load direction changes -->  Less maintainance
  * Lower dynamic loads --> Less structural overhead
* "Overload protection" - the magnetic force transmission will act as a resetable mechanical fuse --> less structural overhead

Potential Risks:
* Oscillating motion-
  * Fatigue risk?
  * Limited output RPM?

The mechanism is targetted at renewable energy applications, which need efficient harnessing of low speed, high torque input, particularly where maintainance is a significant overhead:
* Wind energy
* Small Hydroelectric (e.g. Archimedes screw, water wheel)
* Gravitational energy storage

The "soft backlash" feature could also be beneficial for systems with frequent changes in loading direction
* Flywheel energy storage (enabling a low RPM large diameter rotor?)
* Wave energy

### The Basic Principle
![alt text](./data/output_fixedAx.gif)
The above animation is an accessible rung on the ladder towards the full design.  Here we have two rings of cylindrical magnets, orientated with the poles opposing each other.  Essentially, they act as bevel gears.  If one were to roatate independently of the other, they would reach a high potential energy state where multiple opposing magnets align perfectly.  That potential energy can be released by the driven side rotating, so it does.

The red magnet ring rotates around the red axle, and the blue magnet ring rotates around the blue axle.  The blue axle is angled slightly to the red axle, which allows the magnets to approach and retreat from one another in a well aligned way. There are 20 magnets on the blue ring, and 19 on the red, so for every complete rotation of one ring, the other is one step further round - there are black magnets on each ring to help illustrate this.  The ratio is therefore 19:20.

![alt text](./data/output.gif)

### The Prototype
![alt text](./data/prototype.gif)
