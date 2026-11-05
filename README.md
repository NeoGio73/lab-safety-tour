# Lab Safety Tour

A walkable, browser-based replica of a real chemistry teaching laboratory (Room 250, Building 410, Daytona State College), built in Unity for lab-safety training. Each visit hides five hazards drawn at random from thirty-one; students find them, carry out hands-on tasks, answer emergency questions, evacuate during a fire alarm drill, and finish with a report and a completion certificate.

- **Play the inspection:** https://neogio73.github.io/lab-safety-tour/
- **Safety prelab (read first):** https://neogio73.github.io/lab-safety-tour/prelab/
- **Author:** Prof. John Picione, Department of Biological and Physical Sciences, Daytona State College (ORCID [0009-0007-9182-9664](https://orcid.org/0009-0007-9182-9664))

Nothing to install: it runs in a current desktop web browser that supports WebGL 2. It has been tested on a Windows desktop computer; the download is about 31 MB.

## How it fits into a course

The module is the middle step of a three-part safety sequence that students complete before their first lab:

1. **Safety prelab page** (about twenty minutes): dress code with an interactive check, the ground rules, where the safety equipment is, working with chemicals and heat, labels, safety data sheets and hazard diamonds, waste, emergency response and evacuation routes, and fifteen ungraded practice questions.
2. **The 3D inspection** (this repository): five random hazards, the fire alarm drill, hand washing, then a report and a certificate that students screenshot and upload to the learning management system.
3. **The graded Lab Safety quiz** in the learning management system (D2L Brightspace at Daytona State). Students must score at least 70% before they are admitted to the lab room.

It is used in Organic Chemistry II (CHM 2211) from spring 2027, Organic Chemistry I (CHM 2210) from fall 2027, and Biochemistry (BCH 3023), which meets in the same room.

## Controls

| Action | Keys |
| --- | --- |
| Look around | Click once to capture the mouse, then move it |
| Walk | W A S D or the arrow keys |
| Inspect, pick up, use | Look at it and click, or press E |
| Lower a fume hood sash one step | Look at it and click, or press E |
| Raise a fume hood sash one step | R |
| Close a panel | E or Esc |
| Report | Enter (opens automatically when all hazards are found) |
| New random inspection | N |
| Full screen | F or the on-screen button |
| Free the mouse | Esc |

Whatever you look at gets a gold outline. Clicking a fume hood sash lowers it one step (fully open, working height, closed), the safe direction, which is what a sash left wide open and the fire alarm call for; R raises it. The waste hood's sliding glass panels slide open and closed with a click, and once a panel is open, a click lifts or closes the red lid on the organic waste funnel.

## What is in an inspection

Every hazard is tied to a rule in the course syllabus or to how the rule is enforced in this room:

| \# | Hazard | Source |
|---|---|---|
| 1 | Drink on a bench | Syllabus rule 1, no food or drink |
| 2 | Food on a bench | Syllabus rule 1 |
| 3 | Vape left on a bench | Syllabus rule 2, no smoking |
| 4 | Backpack in the aisle | Room practice: bags on tables or in the knee-space cubbies |
| 5 | Organic solvent on top of the flammables cabinet instead of in the fume hood | Room practice |
| 6 | Flammables cabinet door left open | Room practice |
| 7 | Waste poured onto the closed funnel lid | Syllabus rule 16, waste disposal |
| 8 | Organic solvent poured down the sink | Syllabus rule 16 |
| 9 | Powder spilled on the balance | Syllabus rule 17, leave the work area clean |
| 10 | Broken glass in the wastebasket | Syllabus rule 16, broken glass container |
| 11 | Chemical spill on the floor | Syllabus rule 9, report; spill kit |
| 12 | Eyewash counter cluttered | PPE section, know the eyewash location |
| 13 | Safety shower path blocked | Room practice |
| 14 | Fire extinguisher blocked | Room practice |
| 15 | Fume hood sash left wide open | Syllabus rule 3, work in the hood |
| 16 | Classmate without goggles | Syllabus rule 11, approved eye protection |
| 17 | Hot plate left on, unattended | Syllabus rule 13, hot equipment |
| 18 | Dress code: shorts; short sleeves with skinny jeans; or a strapless top with ripped jeans | Syllabus rules 7 and 8, PPE table |
| 19 | Classmate's sleeve on fire (emergency question) | Emergency procedures |
| 20 | Unlabeled bottle on the bench | Hazard communication: every container labeled |
| 21 | Diethyl ether open on the bench; its label calls for a well-ventilated area | Syllabus rule 3, work in the hood; read the label |
| 22 | Used organic solvent left on the bench (hands-on disposal task) | Syllabus rule 16, waste disposal |
| 23 | Used needle left on the bench (task: sharps container) | Syllabus rule 16, waste disposal; sharps container |
| 24 | Broken beaker on the bench (task: brush, dustpan, broken glass box) | Syllabus rule 16, broken glass container |
| 25 | Classmate splashed in the eye (task: lead them to the eyewash) | Emergency procedures; PPE section, eyewash |
| 26 | Classmate texting with gloves on | Room practice: gloves off before touching phones, handles, keyboards |
| 27 | Solvent fire in a beaker (emergency question) | Emergency procedures; prelab, when water makes it worse |
| 28 | Classmate soaked by a splash (task: safety shower) | Emergency procedures; safety shower |
| 29 | Classmate smelling a flask directly | Room practice: waft, never sniff |
| 30 | Classmate with earbuds in | Room practice: must hear warnings and alarms |
| 31 | 6 M hydrochloric acid left uncapped | Label: keep container tightly closed |

Seven hazards are hands-on tasks rather than a single click: the used solvent must be carried to the waste hood and poured in properly (slide the sash panel open, lift the funnel lid, pour, close the lid); the needle goes in the sharps container; the broken beaker is swept up with the brush and dustpan and emptied into the broken glass box; a splashed classmate is led to the eyewash or the safety shower (cleared first if blocked) for a timed rinse; a floor spill needs a warning and absorbent from the spill kit; and the hot plate is turned off. Wrong steps (the trash, bare hands, a sink, walking through the spill, pouring on the closed lid) are counted in the report.

**Fire alarm drill.** Once in every inspection, after the second hazard is found, the fire alarm sounds. Students shut down if it is safe, walk to the exit (the door to the left of the stockroom; the stockroom door is a wrong step), and choose the route out using the room's posted Emergency Procedures and Evacuation Plan: left to the North Stairwell, or right to the South Stairwell when smoke blocks the left; never the elevator. In some drills a classmate who uses a wheelchair goes to the Area of Rescue Assistance on the stairwell landing. The drill ends at the assembly point by Parking Lot G.

**Safety equipment.** The eyewash, safety shower, fire extinguisher, fire blanket, first-aid kit, spill kit, room power emergency cutoff, gas, air and vacuum shutoff valves, sharps and broken glass containers, waste hood, flammables cabinet with its hazard diamond, emergency procedures flip chart and the doors can all be clicked to learn what they are for.

**Finishing.** When all five hazards are found and the drill is done, students wash their hands at a sink, then type their name on the completion certificate, take a screenshot and upload it to the course. The report lists what was found and missed, with the correct action for anything missed, the time and the number of wrong steps.

## What is in this repository

| Path | Contents |
| --- | --- |
| `index.html`, `Build/`, `TemplateData/` | The Unity WebGL build, served by GitHub Pages |
| `prelab/index.html` | The safety prelab page (single self-contained HTML file) |

The Unity project and its C# scripts are not in this repository, because the project contains purchased assets whose licenses do not allow redistribution. The scripts are available from the author on request.

**Version described in the paper:** the tag `v1.0-preprint` marks the state of this repository described in the manuscript. Later commits may add hazards or fix bugs.

## How it was built

The room was scanned with the LiDAR camera on an iPhone 17 Pro using Polycam, photographed, and rebuilt to measure in Blender and Unity 6 (Universal Render Pipeline). The Blender and Unity work, all of the program code, the first drafts of the hazard texts and the prelab page were produced with a generative AI coding assistant (Claude, Anthropic) connected to Unity and Blender through Model Context Protocol servers. The author directed and checked all of it and checked every hazard text and emergency detail against the course syllabi, the posted procedures and the room itself.

## Credits and licenses

- Laboratory furniture and equipment: Mixall, "Laboratories – Big Pack" (Unity Asset Store, standard end-user license)
- Hover outline: Kronnect, Highlight Plus 2 (Unity Asset Store)
- Fire effect: Hovl Studio, "3D Fire and Explosions" (Unity Asset Store)
- Additional models: BlenderKit (paid plan)
- Student characters and animations: Adobe Mixamo
- One character (Alison): Renderpeople free rigged sample, via CGTrader (Royalty Free license): https://www.cgtrader.com/free-3d-models/character/woman/alison-001-woman-standing

The purchased assets are included only inside the compiled build, as their licenses allow.

## How to cite

Picione, J. Goggles On, Bagels Out: A Randomized Hazard Hunt in a Browser Replica of a Real Teaching Laboratory. *ChemRxiv* **2026**, preprint. DOI to be added.

Related: Picione, J. From Bench to Game Engine: An Instructor-Built Suite of 3D Laboratory Simulations Created with Generative AI. *ChemRxiv* **2026**. https://doi.org/10.26434/chemrxiv.15010988/v1

## Contact

john_picione@daytonastate.edu. Instructors who want to adapt the approach for their own laboratory are welcome to get in touch.
