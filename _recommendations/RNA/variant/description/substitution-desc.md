---
parent: RNA
title: substitution
category: description
---

Format:   **"prefix""position_substituted""reference_nucleotide"">""new_nucleotide"**,  e.g. r.123u>g

**"prefix"**  =  reference sequence used  =  r.<br>
**"position_substituted"**  =  position nucleotide substituted  =  123<br>
**"reference_nulceotide"**  =  nucleotide at reference position =  u<br>
**">"**  =  type of change is a substitution =  ><br>
**"new_nucleotide"**  =  new nucleotide  =  g

---

### Notes

*	**prefix** reference sequences accepted are r. (RNA, based on coding DNA or non-coding DNA).
*	changes involving two or more consecutive nucleotides are described as deletion/insertions (indels) ([_see Deletion/insertion (indel)_](/recommendations/RNA/variant/indel/)).
*	the description r.76_77delinsga is preferred over r.[76u>g;77u>a]  
	*	_**NOTE:**_ by definition this change can not be described as a substitution (like r.76_77uu>ga or r.76uu>ga)
*	it is not correct to describe a frequent variant (polymorphism) as r.76u/g ([_see Discussions_](/recommendations/RNA/variant/substitution/#polymorphism)).
