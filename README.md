# Awesome Clustering Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![GitHub stars](https://img.shields.io/github/stars/themlphdstudent/awesome-clustering-resources.svg)](https://github.com/themlphdstudent/awesome-clustering-resources/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/themlphdstudent/awesome-clustering-resources.svg?color=blue)](https://github.com/themlphdstudent/awesome-clustering-resources/network)
[![License](https://img.shields.io/github/license/themlphdstudent/awesome-clustering-resources.svg?color=blue)](https://github.com/themlphdstudent/awesome-clustering-resources/blob/master/LICENSE)

> Clustering or Cluster analysis is the task of grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar (in some sense) to each other than to those in other groups (clusters). - [Wikipedia](https://en.wikipedia.org/wiki/Cluster_analysis)

------

# Table of Contents

* [Books](#1.-books)
* [Research Papers](#2.-papers)
    - [Survey Papers](##2.1.-survey-papers)
    - [State-of-the-Art Papers](##2.2.-state-of-the-art-papers)
    - [Density Based Clustering Algorithms](##2.3.-density-based-clustering-algorithms)
    - [Distance Based Clustering Algorithms](##2.4.-distance-based-clustering-algorithms)
    - [Time Series Clustering](##2.5.-time-series-clustering)
    - [Text Clustering](##2.6.-text-clustering)
    - [Subspace Clustering](##2.7.-subspace-clustering)
* [Online Courses and Videos](#3.-online-courses)
* [Clustering Datasets](#4.-clustering-datasets)
* [List of Journals](#5.-list-of-journals)

# 1. Books

[Data Clustering](https://books.google.co.in/books/about/Data_Clustering.html?id=edl7AAAAQBAJ&source=kp_book_description&redir_esc=y) by Chandan K. Reddy and Charu C. Aggarwal. This text book covers most of the clustering techniques. Highly recommended to people working in clustering.

[Data Clustering: Theory, Algorithms, and Applications](https://books.google.co.in/books?hl=en&lr=&id=ZXLSVPN1X1sC&oi=fnd&pg=PR1&dq=Data+Clustering:+Theory,+Algorithms,+and+Applications&ots=lqfjO2h01X&sig=ZFUNpMOUJJN5yFt8saOgfMXcqfY#v=onepage&q=Data%20Clustering%3A%20Theory%2C%20Algorithms%2C%20and%20Applications&f=false) by Guojun Gan, Chaoqun Ma and Jianhong Wu. This is a useful compendium of a variety of methods of clustering, for a variety of data types, with numerous measures of similarity, and many examples of algorithms. The ultimate emphasis is on the algorithms, even the implementation in MATLAB or C++.

# 2. Papers

## 2.1. Survey Papers

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Survey of clustering algorithms | IEEE Transactions on Neural Networks | 2005 | [[1]](#1) | [[URL]](https://ieeexplore.ieee.org/abstract/document/1427769) |
| A Survey of Clustering Data Mining Techniques | Springer | 2006 | [[2]](#2) |[[URL]](https://link.springer.com/chapter/10.1007/3-540-28349-8_2) |
| Clustering high-dimensional data: A survey on subspace clustering, pattern-based clustering, and correlation clustering | ACM Transactions on Knowledge Discovery from Data | 2009 | [[3]](#3) | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/1497577.1497578) |
| A Survey of Text Clustering Algorithms | Springer | 2012 | [[4]](#4) |[[URL]](https://link.springer.com/chapter/10.1007/978-1-4614-3223-4_4)
| A Survey of Recent Advances in Hierarchical Clustering Algorithms | The computer journal | 1983 | [[5]](#5) | [[PDF]](https://watermark.silverchair.com/26-4-354.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAngwggJ0BgkqhkiG9w0BBwagggJlMIICYQIBADCCAloGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMYRDNq0J2mfmv0_6rAgEQgIICK5Vg9F5NsjSrqYWR0aL9vNztqj8J375zjs2os7QoH_2mMmMqJsUFoGgaPHcUgaQKMmTUZlSVATCicrBAsEWsoNZvNC6ZiQLHkNPh8khrKLCdpmGIq8tCf4tkjxA_ZQF7CXKlzPEBmwbQn9dYd0UBNI0xeKakL01tOSBYLBSY51_f8mBgC7asQ-4qZKaCAtgk3UVpoOHDxRvn4_8oXErsyy-NuXnvRirPcZ5CjOxk39TzCYL5HyFLRiVRQkwLdqf1qmnr2BrUeNTpQonuDKHVBz12O5pbAXsm7IeakA3bgO_FV7XZNkQbzWfL145FlhK3gjyDoSdWDjlWVes8Xr3DAceTyBfEbY63iONmCyJRoiFex6R63Ty9tYRacCUHaHb8xa32ew__qHxNu3IvnoBHm-OCSi9lOj-2rwa1ZtGQjRY3eqOHBa6lKJAV5jJ4fxRTdu-boJwIeAL04uaNZBasCUZ8AFGjlZZKjgKUMfUjqAATguLKTrbMvVj530Y95wK7BzlPDbK689mTtw5E4nc1sC1mUPGPC5yqOoNo_1MIDp2wrIRA2MrAkexus3i3ArgH_FhyZ7DMYauL4-ombm08zkuA1xawXUYClm0cCukoHw3o9Jncx4JskRBDph0BFCnKXt14aCV7dHuXomyxoBFERRpPS4cI2ZPECynvxhGIj4SFXgqLWD_7ZdIgLSji3nHOF_RbWWWnqNUGujG5Xbl_YpwNp8X9G0AzUJEhIA)
| Subspace clustering for high dimensional data: a review | ACM Sigmod Exploration Newsletter | 2004 | [[10]](#10) | [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.969.7082&rep=rep1&type=pdf)
| Clustering of time series data—a survey | Pattern Recognition | 2005 | [[17]](#17) | [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.115.6594&rep=rep1&type=pdf)


## 2.2. State-of-the-Art Papers

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| DBSCAN | KDD | 1996 | [[6]](#6) | [[PDF]](https://www.aaai.org/Papers/KDD/1996/KDD96-037.pdf)


## 2.3. Density Based Clustering Algorithms

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| DBSCAN | KDD | 1996 | [[6]](#6) | [[PDF]](https://www.aaai.org/Papers/KDD/1996/KDD96-037.pdf)
| OPTICS: ordering points to identify the clustering structure |  ACM Sigmod record | 1999 | [[7]](#7) | [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.407.5572&rep=rep1&type=pdf)
| A distribution-based clustering algorithm for mining in large spatial databases | ICDE |  1998 | [[8]](#8) | [[PDF]](http://www.cip.ifi.lmu.de/~xwxu/publications/icde-98.pdf)
| An efficient approach to clustering in large multimedia databases with noise | AAAI | 1998 | [[9]](#9) | [[PDF]](https://www.aaai.org/Papers/KDD/1998/KDD98-009.pdf)



## 2.4. Distance Based Clustering Algorithms

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|


## 2.5. Time Series Clustering

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
|  |  |  | [[]](#) | [[PDF]]()
|  |  |  | [[]](#) | [[PDF]]()
|  |  |  | [[]](#) | [[PDF]]()
|  |  |  | [[]](#) | [[PDF]]()


## 2.6. Text Clustering

| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Frequent term-based text clustering | KDD | 2002 | [[15]](#15) | [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.84.6420&rep=rep1&type=pdf)
| An Evaluation on Feature Selection for Text Clustering | ICML | 2003 | [[16]](#16) | [[PDF]](https://www.aaai.org/Papers/ICML/2003/ICML03-065.pdf)
|  |  |  | [[]](#) | [[PDF]]()
|  |  |  | [[]](#) | [[PDF]]()
|  |  |  | [[]](#) | [[PDF]]()


## 2.7. Subspace Clustering
| Title | Publication Venue | Year | Reference | URL |
|------|------------|----|--|---|
| Subspace clustering for high dimensional data: a review | ACM Sigmod Exploration Newsletter | 2004 | [[10]](#10) | [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.969.7082&rep=rep1&type=pdf)
Density-Connected Subspace Clustering for High-Dimensional Data | SIAM | 2004 | [[11]](#11) | [[PDF]](https://epubs.siam.org/doi/pdf/10.1137/1.9781611972740.23)
| Entropy-based subspace clustering for mining numerical data | KDD | 1999 | [[12]](#12) | [[PDF]](https://core.ac.uk/download/pdf/48534532.pdf)
| Low rank subspace clustering (LRSC) | Pattern Recognition Letters | 2014 | [[13]](#13) | [[PDF]](https://core.ac.uk/download/pdf/194327517.pdf)
| DUSC: Dimensionality Unbiased Subspace Clustering | ICDM | 2007 | [[14]](#14) | [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.559.1652&rep=rep1&type=pdf)


# 3. Online Courses

**Coursera Machine Learning course by Andrew Ng, Stanford University** [[See Video]](https://www.coursera.org/learn/machine-learning)

**Coursera Machine Learning with Python by IBM** [[See Video]](https://www.coursera.org/learn/machine-learning-with-python)

**Course on Clustering in Machine Learning by Google** [[See Video]](https://developers.google.com/machine-learning/clustering)

**Coursera Clustering Analysis in Data Mining course by University of Illinois at Urbana-Champaign** [[See Video]](https://www.coursera.org/learn/cluster-analysis)


# 4. Clustering Datasets
**Clustering basic benchmark**: [http://cs.joensuu.fi/sipu/datasets/](http://cs.joensuu.fi/sipu/datasets/)


# 5. List of Journals

[Journal of Machine Learning Research](http://www.jmlr.org/)

[IEEE Transactions on Pattern Analysis and Machine Intelligence](https://www.computer.org/csdl/journal/tp)

[Data Mining and Knowledge Discovery](https://www.springer.com/journal/10618/)

[IEEE Access](https://ieeeaccess.ieee.org/)

[Pattern Recognition Letters](https://www.journals.elsevier.com/pattern-recognition-letters)

[ACM SIGKDD Explorations Newsletter](https://www.kdd.org/explorations)



# References

|  |  |
|---|---|
| <a id='1'> [1] </a> | Xu, R., & Wunsch, D. (2005). Survey of clustering algorithms. IEEE Transactions on neural networks, 16(3), 645-678.
| <a id='2'> [2] </a> | Berkhin, P. (2006). A survey of clustering data mining techniques. In Grouping multidimensional data (pp. 25-71). Springer, Berlin, Heidelberg.
| <a id='3'> [3] </a> | Kriegel, H. P., Kröger, P., & Zimek, A. (2009). Clustering high-dimensional data: A survey on subspace clustering, pattern-based clustering, and correlation clustering. ACM Transactions on Knowledge Discovery from Data (TKDD), 3(1), 1-58.
| <a id='4'> [4] </a> | Aggarwal, C. C., & Zhai, C. (2012). A survey of text clustering algorithms. In Mining text data (pp. 77-128). Springer, Boston, MA.
| <a id='5'> [5] </a> | Murtagh, F. (1983). A survey of recent advances in hierarchical clustering algorithms. The computer journal, 26(4), 354-359.
| <a id='6'> [6] </a> | Ester, M., Kriegel, H. P., Sander, J., & Xu, X. (1996, August). A density-based algorithm for discovering clusters in large spatial databases with noise. In Kdd (Vol. 96, No. 34, pp. 226-231).
| <a id='7'> [7] </a> | Ankerst, M., Breunig, M. M., Kriegel, H. P., & Sander, J. (1999). OPTICS: ordering points to identify the clustering structure. ACM Sigmod record, 28(2), 49-60.
| <a id='8'> [8] </a> | Xu, X., Ester, M., Kriegel, H. P., & Sander, J. (1998, February). A distribution-based clustering algorithm for mining in large spatial databases. In Proceedings 14th International Conference on Data Engineering (pp. 324-331). IEEE.
| <a id='9'> [9] </a> | Alexander Hinneburg and Daniel A. Keim. 1998. An efficient approach to clustering in large multimedia databases with noise. In <i>Proceedings of the Fourth International Conference on Knowledge Discovery and Data Mining</i> (<i>KDD'98</i>). AAAI Press, 58–65.
| <a id='10'> [10] </a> | Lance Parsons, Ehtesham Haque, and Huan Liu. 2004. Subspace clustering for high dimensional data: a review. <i>SIGKDD Explor. Newsl.</i> 6, 1 (June 2004), 90–105. DOI:https://doi.org/10.1145/1007730.1007731
| <a id='11'> [11] </a> | Kailing, K., Kriegel, H. P., & Kröger, P. (2004, April). Density-connected subspace clustering for high-dimensional data. In Proceedings of the 2004 SIAM international conference on data mining (pp. 246-256). Society for Industrial and Applied Mathematics.
| <a id='12'> [12] </a> | Cheng, C. H., Fu, A. W., & Zhang, Y. (1999, August). Entropy-based subspace clustering for mining numerical data. In Proceedings of the fifth ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 84-93).
| <a id='13'> [13] </a> | Vidal, R., & Favaro, P. (2014). Low rank subspace clustering (LRSC). Pattern Recognition Letters, 43, 47-61.
| <a id='14'> [14] </a> | Assent, I., Krieger, R., Müller, E., & Seidl, T. (2007, October). DUSC: Dimensionality unbiased subspace clustering. In seventh IEEE international conference on data mining (ICDM 2007) (pp. 409-414). IEEE.
| <a id='15'> [15] </a> | Florian Beil, Martin Ester, and Xiaowei Xu. 2002. Frequent term-based text clustering. In <i>Proceedings of the eighth ACM SIGKDD international conference on Knowledge discovery and data mining</i> (<i>KDD '02</i>). Association for Computing Machinery, New York, NY, USA, 436–442. DOI:https://doi.org/10.1145/775047.775110
| <a id='16'> [16] </a> | Liu, T., Liu, S., Chen, Z., & Ma, W. Y. (2003). An evaluation on feature selection for text clustering. In Proceedings of the 20th international conference on machine learning (ICML-03) (pp. 488-495).
| <a id='17'> [17] </a> | Liao, T. W. (2005). Clustering of time series data—a survey. Pattern recognition, 38(11), 1857-1874.


----


**More to come...**

More items will be added to the repository. Please feel free to suggest other key resources by opening an issue report, submitting a pull request, or dropping me an email @ (samariya.durgesh@gmail.com). Enjoy reading!

Last updated on August 28, 2020
