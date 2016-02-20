---
parent: Protein
title: extension
category: description
---

Format (start): **"prefix""Met1""new-amino-acid""ext""position-new-start"**,  e.g. p.Met1Valext-12

**"prefix"**  =  reference sequence used  =  p.<br>
**"Met1"**  =  translation initiation site  =  Met1<br>
**"new-amino-acid"**  =  variant amino acid  =  Val<br>
**"ext"**  =  type of change is an extension  =  ext<br> 
**"position-new-start"**  =  position new upstream translation initiation codon  =  -12

Format (stop): **"prefix""Ter/\*""position-stop""ext""position-new-stop"**,  e.g. p.Ter110GlnextTer17 (or p.*110Glnext\*17)

**"prefix"**  =  reference sequence used  =  p.<br>
**"Ter/\*"**  =  Ter or \*  =  Ter (or \*)<br>
**"position-stop"**  =  position translation termination codon  =  110<br>
**"new-amino-acid"**  =  variant amino acid  =  Gln<br>
**"ext"**  =  type of change is an extension  =  ext<br> 
**"position-new-start"**  =  position new downstream translation termination codon  =  Ter17 (or *17)

---

### Notes

*	**prefix** reference sequence accepted is p. (protein).
*	variants in the translation initiation codon can have three different consequences
	*	activation of an upstream translation initiation site (i.e. an **extension**)
	*	activation of a downstream translation initiation site (i.e. a **deletion**, p.Gly2Met12del, [_see Protein deletion_](/recommendations/protein/variant/deletion/))
	*	no protein (p.0)
*	when the N-terminal extension does not affect the translation initiation codon the format used is **p.Met1ext-5** and not p.Met1Metext-5
*	originally the format proposed was p.Met1ValextMet-12 but "Met" in "Met-5" was considered to be redundant
*	in the description "extTer#" (alternatively "ext*#") "**#**" is the position of the stop codon in the new reading frame
	*	by definition this position is 2 or higher and C-terminal extension variants can not contain "ext**Ter1**" 
*	when a C-terminal extension in the new reading frame does not encounter a new translation termination (stop) codon the format "**extTer?**" is used
