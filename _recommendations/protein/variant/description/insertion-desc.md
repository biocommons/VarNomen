---
parent: Protein
title: insertion
category: description
---

Format: **"prefix""amino\_acids+positions""ins""inserted\_sequence"**,  e.g. p.Pro45\_Cys46insAlaThr

**"prefix"**  =  reference sequence used  =  p.<br>
**"amino\_acids+positions"**  =  two amino acids with position flanking insertion site  =  Pro45\_Cys46<br>
**"ins"**  =  type of change is an insertion  =  ins<br> 
**"inserted_sequence"**  =  description inserted sequence  =  AlaThr

---

### Note

*	**prefix** reference sequence accepted is p. (protein).
*	the "position" description should contain two **flanking** amino acids, e.g. 45 and 46 but not 46 and 47.
*	“amino\_acids+positions” should be listed from **5’ to 3’**, e.g. 45\_46 but not 46\_45.
*	an insertion can not be described using one amino acid with position, like p.Val23insMet.
*	by definition, duplicating insertions should be described as duplications, not as insertions ([_see Duplication_](/recommendations/protein/variant/duplication/)).
*	in-frame insertions containing a translation termination (stop) codon in the inserted sequence are not described as a deletion-insertion removing the entire C-terminal amino acid sequence. 
*	since for large insertions the amino acids inserted can be derived from the DNA and/or RNA descriptions given, they need not to be described in detail but the total number of inserted amino acids can be given instead (e.g. p.Pro45\_Cys46ins17).
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the inserted sequence which is different when compared to the source, e.g. p.Pro45\_Cys46insGlu100\_Asp120**{Leu111Lys}**
