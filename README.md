# Analyzing and Visualizing Penguin Data with ggplot2
### Data Analysis and Visualization using the **palmerpenguins** dataset in R

In this notebook, I leverage the data analysis and visualization skills learned in my **Data Analysis in R** course at **Eastern University**. Using **ggplot2**, I explore and uncover insights from the **palmerpenguins** dataset through compelling visualizations.

## Running the notebook locally
The first requirement for running the notebook locally is to make sure you have Jupyter notebooks installed. On a Mac, the easiest way to do this is via Homebrew by running `brew install juypter`. Then in the project repo, you can run `jupyter notebook`, which will start a Jupyter notebook on `localhost:8888`.

In order to run R code in Jupyter notebooks, you first have to install the IRKernel in R:
```
install.packages("IRkernel")
IRkernel::installspec(user = TRUE)  # this installs the kernel for Jupyter
```