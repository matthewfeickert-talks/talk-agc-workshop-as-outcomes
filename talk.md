class: middle, center, title-slide
count: false

# Analysis Systems: <br>Workshop Outcomes and Action Items
.large.blue[Matthew Feickert]<br>
.large[(University of Wisconsin-Madison)]
<br>
[matthew.feickert@cern.ch](mailto:matthew.feickert@cern.ch)

[IRIS-HEP AGC workshop 2023](https://indico.cern.ch/event/1260431/contributions/5315157/)

May 5th, 2023

---
# Talk Overview

.large[
* .bold[Time]: 20 minutes talk + 10 minutes questions
* .bold[Notes from organizers]:
   - Summary talk of the workshop from the Analysis Systems perspective
   - Friday morning slot is for the area leads to condense all the workshop discussions of relevance for the area into a plan for the next steps, and most importantly for us a plan towards a showcase event in September
]

---
# Goal to focus on: AGC showcase event 2023

.huge[
* This workshop has focused on what the current state of work is
* As we look to future iterations of the Analysis Grand Challenge need to now look at .bold[what needs to be accomplished] to realize goals raised in discussions.
* Have the [iris-hep/analysis-grand-challenge/ Issue #64](https://github.com/iris-hep/analysis-grand-challenge/issues/64) to guide us as well
* Development and application focuses:
   - Dask-ification of the Analysis Systems ecosystem (reference: [Lindsey's talk](https://indico.cern.ch/event/1260431/contributions/5315181/))
   - Integration of Machine Learning workflows into the Analysis Systems pipeline (reference: [Elliott's talk](https://indico.cern.ch/event/1260431/contributions/5315191/))
   - Exploring `correctionslib` (reference: [Andrew's talk](https://indico.cern.ch/event/1260431/contributions/5315192/))
   - Integration testing of the Analysis Systems pipeline with itself and Coffea-casa
]

---
# Dask-ification and CalVer Coffea

.large[
.center.width-65[[![coffea-transition-plan](figures/coffea-transition-plan.png)](https://indico.cern.ch/event/1260431/contributions/5315181/)]

* Dask Migration: `coffea` .bold[&rarr;] `coffea` CalVer, Awkward .bold[&rarr;] `dask_awkward`,<br> `hist` .bold[&rarr;] `dask_histogram`

.bold[Action items]
   - Perform integration testing with coffea CalVer (pre-)releases
   <br>(AS related Scikit-HEP tools already compatible with Awkward v2)
   - Coordinate discussions with Dask devs for the Institute on reaching HEP scale
   <br>(target SciPy 2023)
   - Upskill in workflows using Dask / Revise AGC analyses
]

---
# ML Pipeline Integration

.large[
- .blue[Point A] 🎉
- .red[Point B] 🌐
- .bold[Point C] 🚀
]

---
# Correctionslib

.large[
- .blue[Point A] 🎉
- .red[Point B] 🌐
- .bold[Point C] 🚀
]

---
# Integration Testing of AS pipeline

.large[
* With all components
* On Coffea-casa
* At all Analysis Facilities
]

---
# Example Slide

.large[
- .blue[Point A] 🎉
- .red[Point B] 🌐
- .bold[Point C] 🚀
]

---
# Summary
.kol-2-3[
- .large[.bold[Important] points]
   - sub points!
   - and more
]
.kol-1-3[
<br>
<br>
<br>
.center.width-100[[![example_logo](assets/logos/logo_IRIS-HEP.png)](https://iris-hep.org/)]
]

---
class: end-slide, center

Backup


---

class: end-slide, center
count: false

The end.
