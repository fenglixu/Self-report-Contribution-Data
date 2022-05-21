# Self-report-Contribution-Data

This repo contains the self-report contribution statement data used in paper "Flat Teams Drive Scientific Innovation". The data is collected from four prestigious journals --- Nature, Science, PNAS, PLOS ONE. 

The datasets can be loaded in as pickle files in Python. Example code:
```
f = open('Nature_Contribution_Data', 'rb')
nature_data = pickle.load(f)
f.close()
```

Data structure:
```
[Paper DOI, Paper Url/Index, Paper Title, List of Authors, Contribution Text/Dictionary]
```

The PLOS ONE dataset is extracted from data published in a previous work:
```
E. A. Corrêa Jr, F. N. Silva, L. da F. Costa and D. R. Amancio 
Arxiv:1609.05545, 2016.
http://arxiv.org/abs/1609.05545
```
