# Finger Scintillator
Finger scintillators with embedded fibers to channel light to attached photo-sensor. Used in applications that require long segmented sections such as hodoscopes and tile scans. The fiber groove follows along the top surface to avoid wasting scintillating material and keep structural integrity of such a small piece, but then gradually dips down to come out parallel to the center of the finger.

![][assembledBatch]

## Theory
The scintillator panel is a doped plastic (available from many suppliers [Eljen](http://www.eljentechnology.com/) being the one used in our prototypes) that emits light in response to being struck by an electron, alpha particle, ion, or high energy photon. The light emitted (blue in our case) is then expected to hit the embedded fiber that is able to absorb that light, and retransmit at the lower green frequency based on the chartists of the fiber. This green light is captured and guided by the fiber to the end of finger where it can be read out. Each event is expected to produce about 30 photons, with a lower number reaching the sensor placed on the fiber side.

## Assembly
Currently the parts must be hand assembled although further production may yield an injection moulding scheme. The following lists the procedure to construct a single finger.

![][drawing]

### Milling
The fingers are cut from 10mm thick scintillator and are made to be square. The groove is cut with a ball mill under water flow to prevent deformation of the plastic due to heat. The milled sides are then polished (Novus plastic polish works well) and then are washed with alcohol.

![][singleFinger]

### Gluing
The optical fibers are cut to length (score and breaking) and the end is polished. It is placed into the groove with a two part optical cement. This binds the fiber to the milled plastic providing a optical bond. Forcing the fiber to match the contour milled

### Covering
The fingers are then covered with either degreased aluminum foil and electrical tape or a coating of reflective spray followed by a dip inside rubberized coating (successful tests have been done with [Spaz Stix Ultimate Mirror Chrome](http://www.hobbyrecreationproducts.com/collections/spazstix-ultimate-mirror-chrome) and [Plasti Dip](https://plastidip.com/)) providing a more even surface finish and reduced labour. THis covering shields external light, and provides higher efficiency by capturing stray photons by reflecting them back towards the fiber optic.

![][covering]

[assembledBatch]: renderings/assembledBatch.jpg "A set of assembled finger scintillators"
[singleFinger]: renderings/singleFinger.jpg "Exploded view of board assembly"
[drawing]: renderings/drawing.jpg "Machinist's drawing used for fabrication"
[covering]: renderings/covering.jpg "Aluminum and tape for light sealing and covering"
