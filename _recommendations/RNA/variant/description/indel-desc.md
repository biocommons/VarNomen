---
parent: RNA
title: deletion/ insertion (indel)
category: description
---

Format:   **"prefix""position(s)deleted""delins""insertedsequence"**,  e.g. r.123_127delinsug

**"prefix"**  =  reference sequence used  =  r.<br>
**"position(s)deleted"**  =  position nucleotide or range of nucleotides deleted  =  123_127<br>
**"delins"**  =  type of change is a deletion-insertion (indel)  =  delins<br>
**"insertedsequence"**  =  description inserted sequence  =  ug<br>

---

### Note

*	**prefix** reference sequences accepted is r. (RNA, based on coding or non-coding transcript).
*	“positionsdeleted” should be listed from **5’ to 3’**, e.g. 123\_126 but not 126\_123.
*	by definition, when **one** nucleotide is replaced by **one** other nucleotide the change is a [_substitution_](/recommendations/RNA/variant/substitution/).
*	under discussion, [_see Proposal for complex variants_](http://www.hgvs.org/mutnomen/HGVS_extend_PT.doc)
	:	{ } (curly braces) can be used to list any change in the inserted sequence ("inserted_sequence") which is different when compared to the source, e.g.  r.123_345delins1101_1222**{1167a>g}**