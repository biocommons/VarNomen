---
parent: RNA
title: deletion
category: description
---

Format:  **"prefix""position(s)_deleted""del"**,  e.g. r.123_127del

**"prefix"**  =  reference sequence used  =  r.<br>
**"position(s)_deleted"**  =  position nucleotide or range of nucleotides deleted  =  123_127<br>
**"del"**  =  type of change is a deletion =  del

---

### Note

*	**prefix** reference sequences accepted is r. (RNA, based on coding or non-coding transcript).
*	“position\_deleted” should contain **one** position, “positions\_deleted” should contain **two different** positions, i.e. 123\_126 but not 123\_123.
*	"positions_deleted" should be listed from **5' to 3'**, e.g. 123_126 but not 126_123.
*	for all descriptions the **most 3 position** possible is arbitrarily assigned to have been deleted (**3'rule**)
