---
parent: Protein
title: duplication
category: description
---

Format: **“prefix”“amino\_acid(s)+position(s)\_duplicated”“dup”**, e.g. p.Glu123\_Cys127dup

**“prefix”**  =  reference sequence used  =  p.<br>
**“amino\_acid(s)+position(s)\_duplicated”**  =  amino acid with position or amino acids with position range duplicated  =  Glu123\_Cys127<br>
**“dup”**  =  type of change is a duplication  =  dup

---

### Notes

*	**prefix** reference sequence accepted is p. (protein).
*	“amino\_acid+position\_duplicated” should contain **one** amino acid with position, “amino\_acids+positions\_duplicated” should contain **two different** positions, i.e. 123_126 but not 123_123.
*	“positions\_duplicated” should be listed from **5’ to 3’**, e.g. 123_126 but not 126_123.
*	for all descriptions the **most C-terminal position** possible is arbitrarily assigned to have been duplicated (**3'rule**)
*	by definition, duplication may only be used when the additional copy is **directly 3'-flanking** of the original copy (a "tandem duplication"). 
*	when there is no evidence that the extra copy of a sequence detected is in tandem (directly 3'-flanking) the original copy, the change can not be described as a duplication, it should be described as **[_an insertion_](/recommendations/protein/variant/insertion/)**.
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the duplicated sequence which is different when compared to the source, e.g. p.Pro45\_Cys80dup**{Gly63Arg}**
