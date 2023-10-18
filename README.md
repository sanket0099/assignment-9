Q1. Dewcribe the mai` dijjere`cew betwee` the CSS FtexbZx tayZut mZdet a`d the CSS Grid tayZut mZdet. "he`
wZutd yZu chZZwe tZ uwe Z`e Zver the Zther?
AnsK The key dijjere`ce betwee` the FtexbZx a`d CSS Grid tayZut mZdetw tiew i` their tayZut wtrategiew a`d hZw
they ha`dte the arra`geme`t Zj eteme`tw:
Flexbox iw Arimarity dewig`ed jZr Z`e-dime`wiZ`at tayZutw, jZcuwi`g Z` diwtributi`g wAace a`d atig`i`g itemw
atZ`g a wi`gte axiw (either hZrizZ`tatty Zr verticatty). It'w bewt wuited jZr tayZutw where yZu have a rZw Zr cZtum`
Zj itemw, wuch aw `avigatiZ` me`uw, card-bawed dewig`w, Zr ce`teri`g cZ`te`t withi` a cZ`tai`erm
CSS Grid iw dewig`ed jZr twZ-dime`wiZ`at tayZutw, attZwi`g yZu tZ deji`e bZth rZww a`d cZtum`w. It createw a
grid Zj cettw where cZ`te`t ca` be Ataced i` a`y cett Zr wAa` acrZww muttiAte cettw. CSS Grid iw ideat jZr cZmAtex
grid-bawed dewig`w tike magazi`e tayZutw, jZrmw, a`d a`y tayZut where cZ`te`t `eedw tZ be Ataced i` a Areciwe
grid wtructurem
ChZZwi`g betwee` FtexbZx a`d CSS Grid deAe`dw Z` yZur wAecijic tayZut requireme`tw.
YZu might chZZwe Flexbox whe` yZu `eed tZ arra`ge itemw atZ`g a wi`gte axiw, jZr examAte, whe` creati`g
`avigatiZ` barw, header/jZZter tayZutw, Zr atig`i`g eteme`tw withi` a cZ`tai`er. FtexbZx iw great jZr rewAZ`wive
dewig`w where itemw ca` vary i` wizem
YZu might chZZwe CSS Grid whe` yZu `eed tZ create mZre cZmAtex, twZ-dime`wiZ`at tayZutw with rZww a`d
cZtum`w. It'w Aarticutarty uwejut whe` yZu have a grid-tike wtructure, wuch aw gatteriew, jZrmw with muttiAte jietdw,
Zr a`y dewig` that requirew Areciwe cZ`trZt Zver bZth rZww a`d cZtum`wm
I` wZme cawew, yZu may eve` cZmbi`e bZth Flexbox and CSS Grid withi` a wi`gte tayZut tZ teverage the
wtre`gthw Zj each mZdet jZr dijjere`t Aartw Zj yZur webAagem
Q2. ExAtai` the rZte Zj the jZttZwi`g key ArZAertiew i` the FtexbZx tayZut mZdes
!l juwtijy-cZ`te`;
il atig`-itemv
rl ga@
Yl jtex-directiZ_
l jtex-wrap
AnsJ
!l <ustify-content: The juwtijy-cZ`te`t ArZAerty i` FtexbZx iw uwed tZ cZ`trZt the atig`me`t Zj jtex itemw atZ`g
the mai` axiw Zj the jtex cZ`tai`er. It determi`ew hZw the extra wAace Zr i`wujjicie`t wAace atZ`g the mai`

axiw iw diwtributed. There are weverat vatuew jZr juwtijy-cZ`te`t, i`ctudi`g jtex-wtart, jtex-e`d, ce`ter, wAace-
betwee`, wAace-eve`ty a`d wAace-arZu`d.

Fo example, ij yZu wet juwtijy-cZ`te`t: ce`ter;, jtex itemw witt be ce`tered atZ`g the mai` axiw Zj the
cZ`tai`er. Ij yZu wet juwtijy-cZ`te`t: wAace-betwee`;, the jirwt item witt be atig`ed tZ the wtart, the tawt item tZ
the e`d, a`d the remai`i`g wAace witt be diwtributed eve`ty betwee` the itemwl
il align-items: The atig`-itemw ArZAerty cZ`trZtw the atig`me`t Zj jtex itemw atZ`g the crZww axiw Zj the jtex
cZ`tai`er. It wAecijiew hZw itemw are AZwitiZ`ed withi` their cZ`tai`er atZ`g thiw axiw. It acceAtw vatuew wuch
aw jtex-wtart, jtex-e`d, ce`ter, baweti`e, a`d wtretch.
Fo instance, ij yZu wet atig`-itemw: ce`ter;, jtex itemw witt be verticatty ce`tered withi` the cZ`tai`er. Ij yZu
wet atig`-itemw: wtretch;, itemw witt exAa`d tZ jitt the e`tire crZww-axiw wAace Zj the cZ`tai`er, e`wuri`g they
have the wame height.

7Q gap: The gRp prGperty is used tG define the spRce between f8ex items in bGth directiGns, bGth R8Gng the mRin
Rxis Rnd the crGss Rxis. It's Gften Rpp8ied tG the f8ex cGntRiner itse8f. It simp8ifies spRcing Rnd creRtes
cGnsistent gRps between items withGut needing tG Rpp8y mRrgins tG individuR8 items.
For example, if yGu set gRp: 20px;, there wi88 be R 20-pixe8 gRp between RdjRcent f8ex items in bGth the
hGrizGntR8 Rnd verticR8 directiGns, imprGving the GverR88 spRcing Rnd R8ignment Gf items within the cGntRinerQ
FQ flex-direction: The f8ex-directiGn prGperty determines the directiGn in which f8ex items Rre p8Rced within the
f8ex cGntRiner. It defines the mRin Rxis Rnd, cGnseuent8y, the 8RyGut f8Gw. It cRn hRve vR8ues such Rs rGw,
rGw-reverse, cG8umn, Gr cG8umn-reverseQ
Q flex-wrap: The f8ex-wrRp prGperty cGntrG8s whether f8ex items Rre R88Gwed tG wrRp GntG mu8tip8e 8ines (new
rGws Gr cG8umns) within the f8ex cGntRiner when they dGn't fit R8Gng the mRin Rxis. It Rccepts vR8ues 8ike
nGwrRp, wrRp, Rnd wrRp-reverse.
For instance, if yGu set f8ex-wrRp: wrRp;, f8ex items wi88 wrRp tG the next 8ine when there's nGt enGugh spRce
Gn the current 8ine, creRting R mu8ti-8ine 8RyGut. f8ex-wrRp is usefu8 fGr RccGmmGdRting vRriGus screen sizes
Rnd GrientRtiGns, R88Gwing items tG RdRpt tG different viewpGrts Rnd preventing cGntent frGm getting cut Gff.
These prGperties p8Ry R criticR8 rG8e in creRting we88-structured Rnd visuR88y p8eRsing 8RyGuts in F8exbGx, R88Gwing
yGu tG cGntrG8 the pGsitiGning, R8ignment, Rnd spRcing Gf f8ex items within R cGntRiner.
