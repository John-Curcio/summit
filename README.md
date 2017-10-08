# Some TODOs:

Note that this WON'T work completely out of the box in DataBricks. Specifically the matplotlib sections - you need some syntax like the following:

`import matplotlib.pyplot as plt`

`import numpy as np`

`fig, ax = plt.subplots()`

`x = np.arange(0, 10, 0.25)`

`ax.plot(x, np.sin(x))`

`display(fig)`


For more info, check <a href="https://docs.databricks.com/user-guide/visualizations/matplotlib-and-ggplot.html">this</a> out.

Also, I think this needs more room for audience participation and quizzes.


