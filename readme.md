# Obround Scintillator Panel
Large scintillator panel with embedded fiber loop to channel light to attached photo-sensor. The tile has a obround pattern with a single fiber to attempt to gather light from as much of the effective area of scintillator and minimize losses from tight curves and open fiber ends. The fiber groove follows along the top surface and comes out perpendicular to end face. This configuration is made for non square panels.

![][exploded]

## Theory
The scintillator panel is a doped plastic (available from many suppliers [Eljen](http://www.eljentechnology.com/) being the one used in our prototypes) that emits light in response to being struck by an electron, alpha particle, ion, or high energy photon. The light emitted (blue in our case) is then expected to hit the embedded fiber that is able to absorb that light, and retransmit at the lower green frequency based on the chartists of the fiber. This green light is captured and guided by the fiber to the end of finger where it can be read out. Each event is expected to produce about 30 photons, with a lower number reaching the sensor placed on the fiber side.

## Assembly
Currently the parts must be hand assembled although further production may yield an injection moulding scheme. The following lists the procedure to construct a single plate.

### Milling
The fingers are cut from 10mm thick scintillator and are 145mm x 145mm. The groove is cut with a ball mill under water flow to prevent deformation of the plastic due to heat. The milled sides are then polished (Novus plastic polish works well) and then are washed with alcohol.

![][side]

### Gluing
The optical fibers are cut to length (score and breaking) and the end is polished. It is placed into the groove with a two part optical cement. This binds the fiber to the milled plastic providing a optical bond. Forcing the fiber to match the contour milled.

### Covering
The fingers are then covered with either degreased aluminum foil and electrical tape or a coating of reflective spray followed by a dip inside rubberized coating (successful tests have been done with [Spaz Stix Ultimate Mirror Chrome](http://www.hobbyrecreationproducts.com/collections/spazstix-ultimate-mirror-chrome) and [Plasti Dip](https://plastidip.com/)) providing a more even surface finish and reduced labour. This covering shields external light, and provides higher efficiency by capturing stray photons by reflecting them back towards the fiber optic.

![][mounting]

[exploded]: renderings/exploded.gif "Exploded animation of obround panel"
[side]: renderings/side.jpg "Side view of milled panel"
[mounting]: renderings/mounting.jpg "Renderings of a panel's mount points"
