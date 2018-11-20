## This repository accompanies the manuscript "Urban colonization in passerines: sexual selection and labile traits"

The data used for analyses can be loaded into R using the *load* function.

Once the data have been loaded. The following data frame elements will be found:
 - *dcol1* and *dcol2*. Are tables with the data used for analyses of plumage dichromatism.
 - *dtestes1* and *dtestes2*. Are tables with the data used for analyses of testes size.
 - *dsdim1* and *dsdim2*. Are tables with the data used for analyses of size dimorphism.
 - *dmatsy1* and *dmatsy2*. Are tables with the data used for analyses of mating system.

Each of the tables described above is associated with a phylogenetic tree object, named *trcol1*, *trcol2*, *trtestes1*, and so forth.

In addition, the elements *noto_obs* and *sscd_obs* contain the statistcs of the tests perfromed using the phylometrics package, with *P*-values contained in the *notoless* and *sscdgrea* elements. The elements *datfpd* and *datfpdurban* contain the results of analyses performed using the caper package.