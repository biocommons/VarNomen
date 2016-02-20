---
parent: Protein
title: deletion/ insertion (indel)
category: description
---

Format:   **"prefix""aminoacid(s)+position(s)deleted""delins""insertedsequence"**,  e.g. p.Arg123_Ser127delinsPheTyr

**"prefix"**  =  reference sequence used  =  p.<br>
**"aminoacid+position(s)\_deleted"**  =  amino acid with position or range of amino acids with positions deleted  =  Arg123\_Ser127<br>
**"delins"**  =  type of change is a deletion-insertion (indel)  =  delins<br>
**"insertedsequence"**  =  description inserted sequence  =  PheTyr<br>

<br>
Format (frame shift):   **"prefix""aminoacid+position\_firstaffected""newaminoacid""fs""Ter+position"**,  e.g. p.Arg123GlyfsTer26 (p.Arg123Glyfs*26)

**"prefix"**  =  reference sequence used  =  p.<br>
**"amino-acid+position\_firstaffected"**  =  first amino acid with position affected  =  Arg123<br>
**"newaminoacid"**  =  variant amino acid  =  Gly<br>
**"fs"**  =  type of change is a frame shift  =  fs<br>
**"Ter+position"**  =  Ter+position stop codon in hifted frame  =  Ter26 (*26)<br>

---

### Notes

*	**prefix** reference sequences accepted are p. (protein).
*	“aminoacid+positionsdeleted” should be listed from **5’ to 3’**, e.g. 123\_126 but not 126\_123.
*	by definition, when **one** amino acid is replaced by **one** other amino acid the change is a [_substitution_](/recommendations/protein/variant/substitution/).
	*	by definition a frame shift of length one does not exist, such a change is a [_Substitution_](/recommendations/protein/variant/substitution/)
*	**frame shifts** are a **special type** of amino acid deletion/insertion affecting an amino acid **between** the first (initiation, ATG) and last codon (termination, stop), replacing the normal C-terminal sequence with one encoded by **another reading frame**.
	*	the description of frame shifts does not include the deletion at protein level from the site of the frame shift to the normal translation termination (stop) codon.
	*	the inserted amino acid sequence is not described (this is not useful), only the first new amino acid and the total length of the new shifted frame are described.
	*	in "fsTer#" # indicates at which codon position the new reading frame ends in a translation termination (stop) codon. The position of the stop in the new reading frame is calculated starting at the first amino acid that is changed by the frame shift, and ending at the first stop codon (Ter#).
	:	_**NOTE**_: the shifted reading frame is thus open for "Ter-1" amino acids. 
	*	a frame shift may be described using a **short** form where "**fs**" follows the first amino acid affected by the change (format p.Arg97fs).
*	when a shifted reading frame does not encounter a new translation termination (stop) codon the format “**fsTer**?” is used.
*	variants on protein level should be described based on the protein reference sequence, irrespective of the underlying DNA variant ([_see General Discussion_](/recommendations/general/#protonly))
	*	the description at protein level does not relate to the change at DNA-level; a 1 nucleotide deletion and a 100 nucleotide deletion may have the same description. 
*	under discussion, [_see Proposal for complex variants_](http://www.hgvs.org/mutnomen/HGVS_extend_PT.doc)
:	{ } (curly braces) can be used to list any change in the inserted sequence ("inserted_sequence") which is different when compared to the source, e.g.  p.Arg123\_Asn155delinsSer608_Asp640**{Gln622Pro}**.
