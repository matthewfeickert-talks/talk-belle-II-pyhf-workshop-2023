class: middle, center, title-slide
count: false

# How to contribute to pyhf development

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
* Most of this talk is just walking you through the [GitHub repo](https://github.com/scikit-hep/pyhf) and the [developer webpage](https://scikit-hep.org/pyhf/development.html)
* Want to stress that .bold[contributions do not have to be code]!
   - Questions
   - Documentation improvement
   - Contributing to roadmap discussions
* Contributions of all kinds are welcome and additional maintainers from experiments other than ATLAS would be of interest (👀)
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
# GitHub Issues

.kol-2-5.huge[
- Give direct feedback and make requests
   - Report bugs
   - Propose new features
   - Ask for new documentation and examples
- Feel free to make many of these
]
.kol-3-5[
.center.width-100[[![github-issues](figures/github-issues.png)](https://github.com/scikit-hep/pyhf/issues)]
]

---
# GitHub Issues

.kol-2-5.huge[
- Give direct feedback and make requests
   - Report bugs
   - Propose new features
   - Ask for new documentation and examples
- Issue templates exist to help guide you
]
.kol-3-5[
.center.width-100[[![issue-template](figures/issue-template.png)](https://github.com/scikit-hep/pyhf/issues)]
]

---
# pyhf User Guide / Tutorial

.kol-2-5.huge[
- More in depth walkthrough of the statistical structure of the models and the pyhf APIs
   - All code runnable as user guide built with Jupyter Book!
- .bold[Contribution ideas]:
   - Work through it, open up [GitHub Issues](https://github.com/pyhf/pyhf-tutorial/issues) on .bold[what else you'd like to see], what .bold[needs more clarification]
]
.kol-3-5[
.center.width-100[[![pyhf-user-guide](figures/pyhf-user-guide.png)](https://pyhf.github.io/pyhf-tutorial/)]
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
