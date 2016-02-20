---
parent: Protein
title: insertion
category: example
---

Insertions are designated by **_"ins"_** after a description of the amino acids flanking the insertion site, followed by a description of the inserted amino acids. When the insertion is large it may be described by its length (e.g. p.Lys2_Leu3ins34). However, it should be possible to derive the inserted sequence from the description at DNA level. Duplicating insertions should be described as duplications ([see Discussion](disc.html#dupins)).

*   p.Lys2_Leu3insGlnSer (alternatively p.K2_L3insQS) describes the cahnge from MKLGHQQQCC to MK**<u>QS</u>**LGHQQQCC
*   p.Arg78_Gly79ins23 describes the in-frame insertion of a 23 amino acid sequence between residues Arg-78 and Gly79\. Such an insertion can e.g. derive from the inclusion of intronic sequences resulting from a change affecting RNA splicing (see [Examples RNA-level](examplesRNA.html#splice)).  
    _**NOTE:**_ the inserted sequence at DNA/RNA level should be specified, where necessary using a sequence database submission (Genbank, EMBL, DDJB) and listing of the accession number.

When an insertion creates a new amino acid at the insertion junction the change is described as an **insertion/deletion** ([see indels](#indel))

*   **in frame**

*   p.Lys2_Met3insGlnSerLys denotes that the sequence GlnSerLys (QSK) was inserted between amino acids Lysine-2 (Lys, K) and Methionine-3 (Met, M), changing MKMGHQQQCC to MK**<u>QSK</u>**MGHQQQCC
*   p.(Pro2_Ile3insGlyTer) is the predicted consequence of the insertion c.6_7insGGGTAG (coding reference sequence NM_000059.3)  
    _**NOTE:**_ this is not described as p.(Ile3_Ile3418delinsGly), a deletion-insertion removing the entire protein coding sequence

*   p.Trp182_Gln183ins17 describes a variant that inserts 17 amino acids between amino acids Trp182 and Gln183  
    **_NOTE:_** it must be possible to deduce the 17 inserted amino acids from the description given at DNA or RNA level