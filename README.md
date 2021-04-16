# pRef_pVal_comparisonExample
Two case files showcasing one (fluidisedBed) that requires pRef and pVal input for PIMPLE algorithm.

Case Files were modified from fluidisedBed tutorial case file, and is solved using twoPhaseEulerFoam.

fluidisedBed_06_waterCont is modified to have water as its continuous phase rather than air.
settlingBed_06_modBCs is has its boundary conditions modified to be equivalent of walls (noSlip velocity BC)
