# Pfat
Pfat, (Protein Function Annotation Tool), a novel software that predicts the function of unknown proteins by using a motif-profile based analysis, where repeat motifs sequences are used for protein family classification and later excluded based on a subsequent phylogenetic analysis on sequence similarities within protein families.


Requirements 
============

Python 2.7 or higher


Installation
============

None


How to run ?
============

To run Pfat, start terminal to enter "$pfat_HOME/bin/" and type:

python pfat

NOTE: 

1) For quick testing, the example input data are provided in the file "$pfat_HOME/example/example.txt"

2) The input sequence must be regular amino acids sequences.

3) All the protein seqeunces can be found in the file "$pfat_HOME/result/*.fasta"


The example of output
============

M3W7C0_FEL is the closest protein with the query protein sequence, the function description about M3W7C0_FEL are listed as below:
<!-- bget:db:default --><!-- uniprot:M3W7C0_FELCA -->ID   M3W7C0_FELCA            Unreviewed;       649 AA.
AC   M3W7C0;
DT   01-MAY-2013, integrated into UniProtKB/TrEMBL.
DT   28-FEB-2018, sequence version 2.
DT   28-FEB-2018, entry version 34.
DE   SubName: Full=G protein signaling modulator 1 {ECO:0000313|Ensembl:ENSFCAP00000006695};
GN   Name=GPSM1 {ECO:0000313|Ensembl:ENSFCAP00000006695};
OS   Felis catus (Cat) (Felis silvestris catus).
OC   Eukaryota; Metazoa; Chordata; Craniata; Vertebrata; Euteleostomi;
OC   Mammalia; Eutheria; Laurasiatheria; Carnivora; Feliformia; Felidae;
OC   Felinae; Felis.
OX   NCBI_TaxID=9685 {ECO:0000313|Ensembl:ENSFCAP00000006695, ECO:0000313|Proteomes:UP000011712};
RN   [1] {ECO:0000313|Ensembl:ENSFCAP00000006695, ECO:0000313|Proteomes:UP000011712}
RP   NUCLEOTIDE SEQUENCE [LARGE SCALE GENOMIC DNA].
RC   STRAIN=Abyssinian {ECO:0000313|Ensembl:ENSFCAP00000006695,
RC   ECO:0000313|Proteomes:UP000011712};
RX   PubMed=17975172; DOI=10.1101/gr.6380007;
RA   Pontius J.U., Mullikin J.C., Smith D.R., Lindblad-Toh K., Gnerre S.,
RA   Clamp M., Chang J., Stephens R., Neelam B., Volfovsky N.,
RA   Schaffer A.A., Agarwala R., Narfstrom K., Murphy W.J., Giger U.,
RA   Roca A.L., Antunes A., Menotti-Raymond M., Yuhki N.,
RA   Pecon-Slattery J., Johnson W.E., Bourque G., Tesler G., O'Brien S.J.;
RT   "Initial sequence and comparative analysis of the cat genome.";
RL   Genome Res. 17:1675-1689(2007).
RN   [2] {ECO:0000313|Ensembl:ENSFCAP00000006695, ECO:0000313|Proteomes:UP000011712}
RP   NUCLEOTIDE SEQUENCE [LARGE SCALE GENOMIC DNA].
RC   STRAIN=Abyssinian {ECO:0000313|Ensembl:ENSFCAP00000006695,
RC   ECO:0000313|Proteomes:UP000011712};
RA   Hillier L.W., Warren W., Obrien S., Wilson R.K.;
RT   "Sequence assembly of the Felis catus genome version 6.2.";
RL   Submitted (SEP-2011) to the EMBL/GenBank/DDBJ databases.
RN   [3] {ECO:0000313|Ensembl:ENSFCAP00000006695}
RP   IDENTIFICATION.
RC   STRAIN=breed Abyssinian {ECO:0000313|Ensembl:ENSFCAP00000006695};
RG   Ensembl;
RL   Submitted (MAR-2013) to UniProtKB.
RN   [4] {ECO:0000313|Ensembl:ENSFCAP00000026995}
RP   IDENTIFICATION.
RC   STRAIN=breed Abyssinian {ECO:0000313|Ensembl:ENSFCAP00000026995};
RG   Ensembl;
RL   Submitted (JAN-2018) to UniProtKB.
CC   -!- CAUTION: The sequence shown here is derived from an Ensembl
CC       automatic analysis pipeline and should be considered as
CC       preliminary data. {ECO:0000313|Ensembl:ENSFCAP00000006695}.
CC   -----------------------------------------------------------------------
CC   Copyrighted by the UniProt Consortium, see http://www.uniprot.org/terms
CC   Distributed under the Creative Commons Attribution-NoDerivs License
CC   -----------------------------------------------------------------------
DR   EMBL; AANG03036307; -; NOT_ANNOTATED_CDS; Genomic_DNA.
DR   EMBL; AANG03036308; -; NOT_ANNOTATED_CDS; Genomic_DNA.
DR   EMBL; AANG03036309; -; NOT_ANNOTATED_CDS; Genomic_DNA.
DR   EMBL; AANG03036310; -; NOT_ANNOTATED_CDS; Genomic_DNA.
DR   STRING; 9685.ENSFCAP00000006695; -.
DR   Ensembl; <a href="http://www.ensembl.org/id/ENSFCAT00000007222">ENSFCAT00000007222</a>; <a href="http://www.ensembl.org/id/ENSFCAP00000006695">ENSFCAP00000006695</a>; ENSFCAG00000007220.
DR   Ensembl; <a href="http://www.ensembl.org/id/ENSFCAT00000034872">ENSFCAT00000034872</a>; <a href="http://www.ensembl.org/id/ENSFCAP00000026995">ENSFCAP00000026995</a>; ENSFCAG00000007220.
DR   eggNOG; KOG1130; Eukaryota.
DR   eggNOG; ENOG410XP6N; LUCA.
DR   GeneTree; ENSGT00530000063126; -.
DR   InParanoid; M3W7C0; -.
DR   OMA; QEPGDDF; -.
DR   OrthoDB; EOG091G04C9; -.
DR   Proteomes; UP000011712; Chromosome D4.
DR   Bgee; ENSFCAG00000007220; -.
DR   GO; GO:0030695; F:GTPase regulator activity; IEA:InterPro.
DR   Gene3D; 1.25.40.10; -; 3.
DR   InterPro; IPR003109; GoLoco_motif.
DR   InterPro; IPR013026; TPR-contain_dom.
DR   InterPro; IPR011990; TPR-like_helical_dom_sf.
DR   InterPro; IPR019734; TPR_repeat.
DR   Pfam; PF02188; GoLoco; 4.
DR   Pfam; PF13176; TPR_7; 1.
DR   SMART; SM00390; GoLoco; 4.
DR   SMART; SM00028; TPR; 6.
DR   SUPFAM; SSF48452; SSF48452; 2.
DR   PROSITE; PS50877; GOLOCO; 4.
DR   PROSITE; PS50005; TPR; 6.
DR   PROSITE; PS50293; TPR_REGION; 2.
PE   4: Predicted;
KW   Complete proteome {ECO:0000313|Proteomes:UP000011712};
KW   Reference proteome {ECO:0000313|Proteomes:UP000011712};
KW   TPR repeat {ECO:0000256|PROSITE-ProRule:PRU00339}.
