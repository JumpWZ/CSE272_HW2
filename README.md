This is the HW2 source code for CSE272 Information Retrieval.

### Usage:
#### Set up the environment
- Python3
- [Surprise](https://github.com/NicolasHug/Surprise)
- required packages: tqdm, joblib, numpy, scipy, six, scikit-learn

#### Download Data
download `Automative.json.gz`as described on canvas and untar it. Put them in the root directory. 
    
#### Main File
See `recommender.ipynb`. This code parses the Amazon Automotive Production Dataset, and perform 3 recommendation algorithms based on user ID, item ID, and ratings.

The critial attributes are those variables in capital letters defined in the second cell. For example, you may set `APPROACH` to `SVD`, `NMF`, or `CoClustering` for different algorithms

#### Notes
ranking_*.out are the ranking output files in "user item ranking" format.


