
                   Important
		   =========
If you do use a basis set with 'all' in its name, be sure to use NOMIT &
CHOMIT (Section 9.8.1) to omit all but those expected to have significant
signals in the spectrum being analyzed.


                    Contents
		    ========
(Metabolite names are in Table 8.1 of ~/.lcmodel/doc/manual.pdf)

The recommended files (i.e., without 'all' in their names) have Ala, Asp, Cr,
PCr, GABA, Glc, Gln, Glu, GPC, PCh, GSH, Ins (or mI), Lac, NAA, NAAG, Scyllo &
Tau.
Those for TE>100ms have Asp, GABA & Glc omitted.

Those with 'all' in their names have all of the above metabolites plus 
Acn, Act, Asc, Cit, Eth, Glyc, 2HG (2-hydroxyglutarate), PAl, PE, Pgc, Pyr, 
Ser, Suc, Thr & Val.

You can also use Section 11.7 to simulate further singlets.


                  Compatibility
		  =============
The TE=0 basis set might be a fair approximation for STEAM (or PRESS) with
TE<11ms.

They would be an excellent approximation if their field strength is within
5MHz of yours (e.g., for 7T, 298MHz and 300MHz are both fine).  LCModel
automatically corrects for such small differences in field strength.
