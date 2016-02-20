---
parent: DNA
title: deletion/ insertion (indel)
category: description
---

Format:   **"prefix""position(s)deleted""delins""insertedsequence"**,  e.g. g.123_127delinsAG

**"prefix"**  =  reference sequence used  =  g.<br>
**"position(s)deleted"**  =  position nucleotide or range of nucleotides deleted  =  123_127<br>
**"delins"**  =  type of change is a deletion-insertion (indel)  =  delins<br>
**"insertedsequence"**  =  description inserted sequence  =  AG<br>

---

### Note

*	**prefix** reference sequences accepted are g., m., c. and n. (genomic, mitochondrial, coding DNA and non-coding DNA).
*	“positionsdeleted” should be listed from **5’ to 3’**, e.g. 123\_126 but not 126\_123.
*	by definition, when **one** nucleotide is replaced by **one** other nucleotide the change is a [_substitution_](/recommendations/DNA/variant/substitution/).
*	under discussion, [_see Proposal for complex variants_](http://www.hgvs.org/mutnomen/HGVS_extend_PT.doc)
	:	{ } (curly braces) can be used to list any change in the inserted sequence ("inserted_sequence") which is different when compared to the source, e.g.  g.123_345delins1101_1222**{1167A>G}**