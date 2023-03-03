class: middle, center, title-slide
count: false

# How to get involved in pyhf development

.huge.blue[Matthew Feickert]<br>
.large[(University of Wisconsin-Madison)]
<br>
[matthew.feickert@cern.ch](mailto:matthew.feickert@cern.ch)

[Belle II pyhf workshop 2023](https://indico.belle2.org/event/8470/contributions/55871/)
<br>
March 3rd, 2023

.middle-logo[]

---
# Introduction and Overview

.huge[
- This work is really all thanks to BNL team
      - Doug Benjamin
      - Ofer Rind
      - Chris Hollowell
- Ongoing process, but today just showing the first (unoptimized) steps that came together pleasantly quickly
- Today showing examples of running at BNL's SDCC Jupyter instance
]

---
# GitHub Discussions

.kol-2-5.huge[
- Think "Stack Overflow for pyhf specifically"
- Both asking and answering questions helps a lot!
   - .bold[Asking]: Helps us understand what isn't clear, what is tricky
   - .bold[Answering]: Helping out to build community knowledge
]
.kol-3-5[
.center.width-100[[![github-discussions](figures/github-discussions.png)](https://github.com/scikit-hep/pyhf/discussions)]
]

---
# Summary

.huge[
- Have a runnable environment for AGC at BNL AF (🚀)
- BNL team is working to make drop-in with custom images well specified and easy
- Things work, but to understand how scaling is working will need to improve the monitoring story
   - Currently don't have Dask dashboards detecting the Dask cluster
- Also need to try other AGC analyses and expand / modify environment
]

---
class: end-slide, center

.huge[Backup]

---

class: end-slide, center
count: false

The end.
