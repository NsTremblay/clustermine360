Clustermine 360
==============

Scripts to parse store and present large quantities of Secondary Metabolite Biosynthetic Pathway information

Background
==============

There is a increasingly large amount of information available on microbial secondary metabolite biosynthesis. In particular, gene clusters containing polyketide synthases (PKS) and non-ribosomal peptide synthetases (NRPS) have received significant attention which has resulted in the sequencing of many of these clusters during the past decade. However, in order to take advantage of this data, it needs to be easily accessible and discoverable. While the sequences themselves are generally available on NCBI, they are frequently difficult to locate partially due to the large amounts of information hosted in their databases. In order to accelerate research in this area, it would be beneficial to have this information gathered together so that existing data can be leveraged to the fullest.

While there are some existing databases in this space, most of them are static and are not being actively updated. Few institutions or research groups have the resources to maintain ongoing manual curation. However, new data is being generated and there needs to be an easy way to add and update the database with new information. To this end, we have designed this database to employ as much auto-curation as possible. That is to say, to use the power of the computer to assist in curation of gene cluster data. Additionally, we have tried to adopt a community approach to the design of our database. Interested individuals are able to sign up for a free account allowing them to add or update data. By crowd-sourcing, it allows participation by those who are interested in contributing while also lessening the need for a dedicated full-time curator.

Community-based curation, however, also has some unique challenges. In particular, it can be difficult to ensure high levels of data quality. We have tried to address this issue by ensuring that users only need to provide a few details while the bulk is derived from other sources or analysis tools. For example, clusters in the database can be sorted by phylum and species. The user does not need to provide the species, genus, phylum and complete lineage of the producer of a given cluster. This data is retrieved directly from NCBI databases minimizing the risk of bad data being input by a user. Additionally, as another example, we use the antibiotic And Secondary Metabolite SHell (antiSMASH) tool to provide analysis on each cluster. The results are parsed and used to automatically assign characteristics such as pathway type to each cluster.

Accessibility
=============

We are working very hard at bringing an ever growing number of secondairy metabolite biosynthetic pathways. We only have the capacity to store what is on the website at the moment. We hope to be able to bring new clusters when our infrastructure will permit.

