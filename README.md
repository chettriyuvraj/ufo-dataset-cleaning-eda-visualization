# ufo-dataset-cleaning-eda-visualization
Performing elementary cleaning, EDA and visualization on a 'UFO sightings' dataset sourced from Kaggle. 
**Dataset**: [UFO sightings in the last century.](https://www.kaggle.com/NUFORC/ufo-sightings)


## How to run: 

1. Simple view - This is an HTML rendering of the Jupyter Notebook viewed through nbviewer: 

  [Performing elementary cleaning, EDA and visualization on a 'UFO sightings' dataset sourced from Kaggle]            (https://nbviewer.jupyter.org/github/chettriyuvraj/ufo-dataset-cleaning-eda-visualization/blob/master/ufo_dataset_notebook.html)

  (Do wait for 10-15 minutes for the plots to render) 

  **The above link has about 8-10 pie/bar/scatter plots Please report issue if plots not rendering.**

  or


2. Clone the repository and run the entire .ipynb notebook provided on Jupyter Notebooks - might take 15-20 minutes to perform computations plus rendering the plots. Requirements: Jupyter notebook + plotly (No separate requirements file attached).



## Issues: 

1. Plots do not render - the plotly plots mysteriously do not render at times when viewed through the nbviewer link. Possible issue with the screen size. 
**Fix/Workaround**: Wait for 10-15 minutes. Else, try viewing through a mobile device, usually work for most mobile screens. 

2. IPYNB notebook does not render plots - both on Github as well as nbviewer. Do connect if any fix found/known.
**Fix/Workaround**: Notebook converted to html and viewed through nbviewer - still presenting issues rendering plots on some devices. 

## Future 
1. Figure out how to fix rendering issues to view Jupyter Notebook directly using Github/nbviewer hassle-free on all devices. 
2. Reduce data cleaning computation time (takes 15/20 minutes).
3. Split datetimes column to separate out time and create visualizations on the timeframes of sightings. 

