---
parent: RNA
title: conversion
category: description
---

Format: **"prefix""positions_converted""con""positionsreplacingsequence"**,  e.g. r.123_345con888_1110

**"prefix"**  =  reference sequence used  =  r.<br>
**"positions_converted"**  =  range of nucleotides converted  =  123_345<br>
**"con"**  =  type of change is a conversion =  con<br> 
**"positionsreplacingsequence"**  =  description of replacing sequence  =  888_1110
 
---

### Note

*	**prefix** reference sequences accepted is r. (RNA, based on coding or non-coding transcript).
*	the region converted ("positionsconverted") should _**start**_ and _**end**_ with a variant nucleotide.
*	“positionsconverted” should contain **two different** positions, i.e. 123\_126 but not 123\_123.
*	“positionsconverted” should be listed from **5’ to 3’**, e.g. 123\_126 but not 126\_123.
*	under discussion, [_see Open Issues_](/recommendations/open-issues/#imperfectcopy)
	:	{ } (curly braces) can be used to list any change in the converted sequence ("positionsreplacingsequence") which is different when compared to the source, e.g. r.123_345con888_1110**{999a>g}**
