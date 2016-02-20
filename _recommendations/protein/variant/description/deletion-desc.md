---
parent: Protein
title: deletion
category: description
---

Format: **“prefix”“amino_acid(s)+position(s)_deleted”“del”**, e.g. p.Glu123_Cys127del

**“prefix”**  =  reference sequence used  =  p.<br>
**“amino_acid(s)+position(s)_deleted”**  =  amino acid+position or amino acids+position range deleted  =  Glu123_Cys127<br>
**“del”**  =  type of change is a deletion  =  del

---

### Notes

*	**prefix** reference sequence accepted is p. (protein).
*	“position\_deleted” should contain **one** position, “positions\_deleted” should contain **two different** positions, i.e. 123\_126 but not 123\_123.
*	“position(s)\_deleted” should be listed from **5’ to 3’**, e.g. 123\_126 but not 126\_123.
*	for all descriptions the **most 3 position** possible is arbitrarily assigned to have been deleted (**3'rule**)
*	deletions remove either a small internal segment of the protein (**in-frame deletion**), part of the N-terminus of the protein (**initiation codon change**) or the entire C-terminal part of the protein (**nonsense variant**). A _**nonsense**_ change is a special type of deletion removing the entire C-terminal part of a protein starting at the site of the variant (specified _**<small><font color="#FF0000">2013-03-16</font></small>**_).
*	 **nonsense** variants are a special type of amino acid deletion, introducing an immediate translation termination (stop), described as a substitution ([_see Substitution_](/recommendations/protein/variant/substitution/))
