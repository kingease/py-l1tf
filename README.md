py-l1tf
=======

Python implementation of L1 trend filtering algorithm using the [cvxopt](http://cvxopt.org/) library.
The paper describing this technique can be found [here](http://web.stanford.edu/~gorin/papers/l1_trend_filter.pdf)

Here are some different fits for a timeseries downloaded from [here](http://www.barchartmarketdata.com/datasamples/US%20Futures%20Tick%20Query.csv)

![Different fits by changing the delta parameter](https://raw.githubusercontent.com/elsonidoq/py-l1tf/master/l1tf/example/fits.png)

This can be also very usefull for removing outliers

![Different fits by changing the delta parameter](https://raw.githubusercontent.com/elsonidoq/py-l1tf/master/l1tf/example/outliers.png)

