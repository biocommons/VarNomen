---
layout: default-md
title: SVD-WG008
category: SVD-WG
---

## Community Consultation

### Proposal SVD-WG008 (RefSeq)

*	Status: <font color="red">open</font>
	:	proposal SVD-WG008 opens for **Community Consultation** on July 15 (2019), will close September 30 (2019). 

The proposal suggests to specify the HGVS recommendations for acceptable Reference Sequences.

### Backgound

A sequence variant is defined in the context of a **reference sequence** which MUST be referred to by means of a unique **sequence identifier**. Because a reference sequence defines the numbering system (http://varnomen.hgvs.org/bg-material/numbering/) and default state of a sequence (e.g. coding transcript, non-coding transcript), accurately interpreting a sequence variant requires that both the reference sequence and its reference sequence identifier are unchangeable.

*	RNA fusion transcripts are described following the format to describe a fusion between two DNA molecules (translocations), i.e. using **"::"**.

* * *

#### Examples

*	translocation fusion:  NM\_152263.2:r.-115\_775::NM\_002609.3:r.1580\_\*1924
	:	a TPM3-PDGFRB fusion transcript where nucleotides r.-115 to r.775 (reference transcrip NM\_152263.2, TPM3 gene) are coupled to nucleotides r.1580 to r.\*1924 (reference transcript NM\_002609.3, PDGFRB gene)
*	deletion fusion:  NM\_002354.2:r.-358_555::NM\_000251.2:r.212\_\*279
	:	EPCAM-MSH2 fusion transcript where nucleotides r.-358 to r.555 (reference transcrip NM\_002354.2, EPCAM gene) are coupled to nucleotides r.212 to r.\*279 (reference transcript NM\_000251.2, MSH2 gene)
*	NOTES
	:	a format like "**::aggcucccuugg::**" is used to indicate the insertion of a 12 nucletoide sequence (aggcucccuugg) between two fusion transcripts

* * *

#### NOTE

All fusion transcripts are described using the same format irrepsective of whether they derive from inter-chromosomal or intra-chromosomal rearrangements (translocation, deletion, inversion)
