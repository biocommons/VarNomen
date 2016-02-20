---
parent: DNA
title: inversion
category: description
---

Format:   **"prefix""positionsinverted""inv"**,  e.g. g.123_345inv

**"prefix"**  =  reference sequence used  =  g.<br>
**"positionsinverted"**  =  range of nucleotides inverted  =  123_345<br>
**"inv"**  =  type of change is an inversion  =  inv

---

### Note

*	**prefix** reference sequences accepted are g., m., c. and n. (genomic, mitochondrial, coding DNA and non-coding DNA).
*	by definition, the region inverted ("positionsinverted") contains **more then one nucleotide**. The description g.234inv is therefore not allowed; a one nucleotide inversion should be described as a [_Substitution_](/recommendations/DNA/variant/substitution/). 
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the inverted sequence ("positions_inverted") which is different when compared to the source, e.g. g.123_345inv**{233A>G}**.
*	inversions are not used on Protein level.
