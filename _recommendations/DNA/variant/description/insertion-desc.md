---
parent: DNA
title: insertion
category: description
---

Format: **"prefix""positions\_flanking""ins""inserted\_sequence"**,  e.g. g.123\_124insAGC

**"prefix"**  =  reference sequence used  =  g.<br>
**"positions\_flanking"**  =  position two nucleotides flanking insertion site  =  123\_124<br>
**"ins"**  =  type of change is an insertion  =  ins<br> 
**"inserted_sequence"**  =  description inserted sequence  =  AGC

---

### Note

*	**prefix** reference sequences accepted are g., m., c. and n. (genomic, mitochondrial, coding DNA and non-coding DNA).
*	the "position" description should contain **two flanking nucleotides**, e.g. 123 and 124 but not 123 and 125.
*	“positions\_flanking” should be listed from **5’ to 3’**, e.g. 123\_124 but not 124\_123.
*	an insertion can not be described using one nucleotide position, like g.123insG
*	by definition, duplicating insertions should be described as duplications, not as insertions ([_see Duplication_](/recommendations/DNA/variant/duplication/)).
*	when the inserted sequence is very long ....
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the inserted sequence which is different when compared to the source, e.g. g.123\_124ins100\_120**{111A>G}**
