### Open-source data from the Mirroring paper 

#### Data Format

Mirror movements and fine-finger function was measured in N=53 patients and N=14 age-matched controls. Participants were measured within the first 2 weeks after stroke and at weeks 4, 12, 24 and 52 over the year. Data is saved in a text file format in the file 'data_mirroring2017.txt'. Each row in the file corresponds to one measurement per participant/session. The file has the fields:

- SN          : unique subject identifier
- grp         : group identifier 

​                          1. control
                          2. non-paretic hand
                          3. paretic hand

- week        : week at which measurement was carried out
- severe      : severity of patient group which was used for paretic analysis in paper

​                          0. not-defined
                          1. patients with MEP at week 2
                          2. patients with no MEP at week 2

- FM          : Fugl-Meyer score on the upper-limb (out of 66)
- mvf         : average strength on the hand (in newtons)
- mm          : degree of mirroring on this hand
- mm_hom      : degree of mirroring on homologous pair on this hand
- mm_het      : degree of mirroring on heterologous pair on this hand


- ens         : degree of enslaving on this hand