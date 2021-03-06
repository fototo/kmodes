.. image:: https://landscape.io/github/nicodv/kmodes/master/landscape.svg?style=flat
    :target: https://landscape.io/github/nicodv/kmodes/master
    :alt: Code Health

kmodes
======

Description
-----------
Pure Python implementations of the k-modes and k-prototypes clustering
algorithms.

k-modes is used for clustering categorical variables. It defines clusters
based on the number of matching categories between data points. (This is
in contrast to the more well-known k-means algorithm, which clusters
numerical data based on Euclidean distance.) The k-prototypes algorithm
combines k-modes and k-means and is able to cluster mixed numerical /
categorical data.

Implemented are:

- k-modes [1][2]
- k-modes with initialization based on density [3]
- k-prototypes [1]

The code is modeled after the k-means module in scikit-learn and has the
same familiar interface.

Usage examples of both k-modes ('soybean.py') and k-prototypes
('stocks.py') are included.

I would love to have more people play around with this and give me
feedback on my implementation.

Enjoy!

References
----------

[1] Huang, Z.: Clustering large data sets with mixed numeric and categorical
values, Proceedings of the First Pacific Asia Knowledge Discovery and Data
Mining Conference, Singapore, pp. 21-34, 1997.

[2] Huang, Z.: Extensions to the k-modes algorithm for clustering large data
sets with categorical values, Data Mining and Knowledge Discovery 2(3),
pp. 283-304, 1998.

[3] Cao, F., Liang, J, Bai, L.: A new initialization method for categorical
data clustering, Expert Systems with Applications 36(7), pp. 10223-10228.,
2009.

Requirements
------------
Tested on:

- Python 2.7 / 3.4
- NumPy 1.9
