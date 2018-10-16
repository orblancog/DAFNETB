oblancog 2018/OCT/16


The main file is job.madx.
DAFNE has two main ring MRe and MRp. Here is the model of the MRp (positron ring).
Linear optics should be OK, but multipoles might not because they come from my
own translator from mad -> madx.


cur.madx : contains the quadrupoles and correctors strength. K1 is proportional to these magnets currents.
bendx_siddarta1 : some dipoles model
wig : wiggler model
kick : injection kickers
bpm: bpms and rf cavity
drift : drifts
chv : correctors
sxp : sextupoles
skew : skew quadrupoles
quad : quads during the siddharta experiment
ir1 : ir1_region configuration, where experiments are installed
ir2 : ir2_region. Not used. Beams are separated.
ring : the line declaration
p_loc : parameters


