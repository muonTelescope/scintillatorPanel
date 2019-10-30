# Scintillator Panel
Large scintillator panel with embedded fibre loop to channel light to attached photo-sensor. The tile has a loop pattern with a single fibre to attempt to gather light from as much of the effective area of scintillator and minimize losses from tight curves and open fibre ends. The fibre groove follows along the top surface and comes out perpendicular to end face.

![][assembled]

## Theory
The scintillator panel is a doped plastic (available from many suppliers [Eljen](http://www.eljentechnology.com/) being the one used in our prototypes) that emits light in response to being struck by an electron, alpha particle, ion, or high energy photon. The light emitted (blue in our case) is then expected to hit the embedded fibre that can absorb that light, and retransmit at the lower green frequency based on the chartists of the fibre. This green light is captured and guided by the fibre to the end of the panel where it can be read out. Each event is expected to produce about 30 photons, with a lower number reaching the sensor placed on the fibre side.

## Assembly
Currently the parts must be hand assembled although further production may yield an injection moulding scheme. The following lists the procedure to construct a single plate.

### Milling
The panel starts as 200mm x 200mm and 10mm thick [Eljen EJ-200](https://eljentechnology.com/products/plastic-scintillators/ej-200-ej-204-ej-208-ej-212) scintillator and the corner is chamfered at 1 inch. The groove is cut with a 1.3mm ball mill under water flow to prevent deformation of the plastic due to heat and provide sufficent clearence. The milled sides are then polished with Novus plastic polish and then are washed clean with alcohol to remove and surface residue or contamination.

![][exploded]

### Gluing
The [Kuraray K-11](https://www.kuraray.com/products/psf) wavelength shifting fibers are cut to length (score and breaking) and the end is polished. It is placed into the groove with a two-part optical cement. This binds the fibre to the milled plastic providing an optical bond. Forcing the fibre to match the contour milled.

### Covering
The fingers are then covered with either degreased aluminium foil and electrical tape or a coating of reflective spray followed by a dip inside rubberized coating (successful tests have been done with [Spaz Stix Ultimate Mirror Chrome](http://www.hobbyrecreationproducts.com/collections/spazstix-ultimate-mirror-chrome) and [Plasti Dip](https://plastidip.com/)) providing a more even surface finish and reduced labour. This covering shields external light, and provides higher efficiency by capturing stray photons by reflecting them back towards the fibre optic.

[assembled]: renderings/scintillatorPanel.png "When assembled only the coating and fibre exit is visible"
[exploded]: renderings/scintillatorPaneExploded.png "An exploded view of the two coatings, panel and fibre"
