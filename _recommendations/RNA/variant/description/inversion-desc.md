---
parent: RNA
title: inversion
category: description
---

Format:   **"prefix""positionsinverted""inv"**,  e.g. r.123_345inv

**"prefix"**  =  reference sequence used  =  r.<br>
**"positionsinverted"**  =  range of nucleotides inverted  =  123_345<br>
**"inv"**  =  type of change is an inversion  =  inv

---

### Note

*	**prefix** reference sequences accepted is r. (RNA, based on coding or non-coding transcript).
*	by definition, the region inverted ("positionsinverted") contains **more then one nucleotide**. The description r.234inv is therefore not allowed; a one nucleotide inversion should be described as a [_Substitution_](/recommendations/RNA/variant/substitution/).
* large inversions on the RNA level are rare; when a DNA sequence inverts all RNA splicing signals disappear and are replaced by signals from the other chromosome strand.
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the inverted sequence ("positions_inverted") which is different when compared to the source, e.g. r.123_345inv**{233a>g}**.
*	inversions are not used on Protein level.
