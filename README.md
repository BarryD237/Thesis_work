# Thesis_work

#### R.emersonii.xlsx
Excel sheet containing all predicted gene annotations. 

#### Excel to SQLite
script to convert R.emersonii.xlsx to a SQLite ".db" file. 

#### R.emersonii.tar.gz
zipped R.emersonii.db file (zipped due to file size constraints). 

#################################################################

#### BLAST_hits:Sec_Met.pdf
top BLAST hits for each gene in Clusters. If clusters contained
Secondary Metabolite information, corresponding MiBiG secondary
metabolite code was looked up. 

#################################################################

#### python scripts
does what it says on the tin

#################################################################

#### compressedMiBiG.tar.gz

CONTENTS: 

---html_content
      |
      |-css
      |-img
      |-index.html
      |-js
      |-networks
       
This folder contains all of the files neccessary to view the 
interactive 'index.html' in a web browser. 

This network shows all MiBiG secondary metabolite database 
entries as a node, any entries involved in the same pathway
eg "Aflatoxin biosynthetic gene cluster" are connected by an edge. 

None of R.emersonii's nodes connected to MiBiG nodes.

This result was frustrating, as this method of creating a 
distance matrix from BLAST similarity scores was something I had read
and discussed at length online. If I had more time, I would look
at the code used to run BiGSCAPE and find what threshold score was 
used to qualify a node - node connection. Lowering this score might 
include R.emersoniis genes in relevant BGCs. 

