# Self-report-Contribution-Data

This repo contains the self-report contribution statement data used in paper "Flat Teams Drive Scientific Innovation". The data is collected from four prestigious journals --- Nature, Science, PNAS, PLOS ONE. 

The datasets can be loaded in as pickle file in Python. Example code:
```
f = open('Nature_Contribution_Data', 'rb')
nature_data = pickle.load(f)
f.close()
```

Data structure:
```
[Paper DOI, Paper Url/Index, Paper Title, List of Authors, Contribution Text/Dictionary]
```
