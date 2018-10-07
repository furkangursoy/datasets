## Datasets by Furkan Gürsoy

This is the webpage where I share datasets for public use.

### Inploid

Inploid is a social question & answer website in Turkish. Users can follow others and see their questions and answers on the main page. Each user is associated with a reputability score which is influenced by feedback of others about questions and answers of the user. Each user can also specify interest in topics. The data is crawled in June 2017 and consist of 39,750 nodes and 57,276 directed links between them. In addition, for each user, reputability scores and top five topics are included in the dataset. Usernames and topics are anonymized. Dataset description is available in the README file.

Please cite:

+ F. Gursoy and D. Gunnec, Influence maximization in social networks under deterministic linear threshold model, Knowledge-Based Systems. Accepted, 2018. https://doi.org/10.1016/j.knosys.2018.07.040

[Click here to download.](https://github.com/furkangursoy/datasets/blob/master/inploid.zip?raw=true)


### Synthetics Networks with Communities based on ComAwareNetGrowth

10 syhnthetically generated, undirected, unweighted networks with communities based on *ComAwareNetGrowth* model. More networks with different characteristics can be created by using the source code at https://github.com/furkangursoy/ComAwareNetGrowth. Refer to the published study for more information on how these networks are generated. Below table presents certain network statistics for the 10 sample networks. Dataset description and further information is available in the README file.

| Network   | n     | m      | nOfCom         | ClusCoef              | AvgPathLen        | Modularity | Diameter | PowerLawExp      |
|-----------|-------|--------|----------------|-----------------------|-------------------|------------|----------|------------------|
| Network1  | 300   | 1600   | 3              | 0.12                  | 2.74              | 0.11       | 6        | 2.24             |
| Network2  | 5000  | 18000  | 3              | 0.06                  | 4.33              | 0.27       | 10       | 2.57             |
| Network3  | 9000  | 50000  | 6              | 0.05                  | 4.00              | 0.32       | 9        | 2.18             |
| Network4  | 4000  | 50000  | 6              | 0.08                  | 3.07              | 0.58       | 6        | 1.72             |
| Network5  | 1000  | 20000  | 4              | 0.15                  | 2.33              | 0.21       | 4        | 1.56             |
| Network6  | 1000  | 2000   | 8              | 0.11                  | 5.08              | 0.22       | 11       | 3.24             |
| Network7  | 500   | 2000   | 2              | 0.10                  | 3.28              | 0.22       | 8        | 2.35             |
| Network8  | 1000  | 10000  | 4              | 0.11                  | 2.75              | 0.35       | 5        | 1.80             |
| Network9  | 10000 | 30000  | 5              | 0.03                  | 4.80              | 0.48       | 12       | 2.56             |
| Network10 | 42788 | 410736 | 10             | 0.04                  | 3.94              | 0.65       | 10       | 1.80             |

Please cite:

+ F. Gursoy and B. Badur, A Community-aware Network Growth Model for Synthetic Social Network Generation, 5th Int'l Management Information Systems Conference. 2018

[Click here to download.](https://github.com/furkangursoy/datasets/blob/master/ComAwareNetGrowth.zip?raw=true)
