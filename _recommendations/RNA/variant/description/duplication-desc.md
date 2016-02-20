---
parent: RNA
title: duplication
category: description
---

Format:   **"prefix""position(s)\_duplicated""dup"**,  e.g. r.123\_345dup

**"prefix"**  =  reference sequence used  =  r.<br>
**"position(s)\_duplicated"**  =  position nucleotide or range of nucleotides duplicated  =  123\_345<br>
**"dup"**  =  type of change is a duplication  =  dup

---

### Note

*	**prefix** reference sequences accepted is r. (RNA, based on coding or non-coding transcript).
*	“position\_deleted” should contain **one** position, “positions\_deleted” should contain **two different** positions, i.e. 123\_126 but not 123\_123.
*	“positions\_deleted” should be listed from **5’ to 3’**, e.g. 123\_126 but not 126\_123.
*	for all descriptions the **most C-terminal position** possible is arbitrarily assigned to have been duplicated (**3'rule**)
*	by definition, duplication may only be used when the additional copy is **directly 3'-flanking** of the original copy (a "tandem duplication"). 
*	when there is no evidence that the extra copy of a sequence detected is in tandem (directly 3'-flanking) the original copy, the change can not be described as a duplication, it should be described as **[_an insertion_](/recommendations/RNA/variant/insertion/)**.
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the duplicated sequence which is different when compared to the source, e.g. r.123\_345dup**{234a>g}**
