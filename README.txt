CHEMISTRY SIMULATIONS · nsbsims
HSC Chemistry · Module 5: Equilibrium and Acid Reactions

OPENING THE SIMULATIONS
Double-click index.html. It is the main page and links to all fourteen simulations.
Every page is one self-contained file. Nothing needs to be installed and no
internet connection is needed. The only links that go online are the two
sources on the cycad page.

WHAT IS IN THIS FOLDER
index.html               Main page
collision-theory/        0   Collision Theory Simulation (with its worksheet PDF)
reversible-or-not/       1   Reversible or Not?
dynamic-equilibrium/     2   Dynamic Equilibrium Box (includes the water transfer model)
entropy-enthalpy/        3   Why Some Reactions Never Come Back
le-chatelier/            4   Le Chatelier Lab
graph-detective/         5   Graph Detective
energy-profiles/         6   Energy Profiles and Rates
keq-builder/             7   Keq Builder and Q vs K
ice-trainer/             8   ICE Table Trainer
colorimeter/             9   Virtual Colorimeter Prac
dissolving/              10  Dissolving Up Close
precipitation/           11  Precipitation Spot Plate
ksp/                     12  Will It Precipitate?
cycad/                   13  Cycad Detoxification

ADDING A WORKSHEET LINK
Each simulation has a hidden "Worksheet" link at the bottom of the page, in the
same style as the one on the collision theory simulation. To switch it on:

1. Put your PDF in that simulation's folder, for example
       le-chatelier/worksheet.pdf
2. Open le-chatelier/index.html in a text editor and find this line near the
   top of the file (search for WORKSHEET_URL):
       <script>window.WORKSHEET_URL = "";</script>
3. Type the file name between the quotes:
       <script>window.WORKSHEET_URL = "worksheet.pdf";</script>

The link appears as soon as a file name is there. A full web address works too.

LIVE SITE
This folder is the nsbsims/chemistry repository, published with GitHub Pages:
    https://nsbsims.github.io/chemistry/                chemistry main page
    https://nsbsims.github.io/chemistry/le-chatelier/   (and so on)
The site-wide home page listing every subject is https://nsbsims.github.io/
(the nsbsims/nsbsims.github.io repository).
All links between pages are relative, so the site also works offline.

NOTES ON THE CHEMISTRY
- Ksp values (simulation 12) are 25 °C values. Please check them against your
  copy of the NESA data sheet before students rely on them.
- The ICE Table Trainer never needs the quadratic formula. Small-x problems are
  only generated when x is under 5% of the initial concentration.
- The colorimeter prac has a deliberate, realistic systematic error (explained
  on the page), so students' K comes out a little above the built-in value.
- Numbers in the cobalt chloride system, the energy profile model, the particle
  models and the cycad leaching model are illustrative. Each page says so.
- The cycad page summarises two published sources, listed on the page.
