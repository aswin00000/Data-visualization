# Data-visualization
data visualization using seaborn
basics <br>
1 Set up the notebook 
 > import pandas as pd<br>
 > pd.plotting.register_matplotlib_converters()<br>
 > import matplotlib.pyplot as plt<br>
 > %matplotlib inline<br>
 > import seaborn as sns<br>      

2 load the data
 >data = pd.read_csv(fifa_filepath, index_col="Date", parse_dates=True)
 >
 >
3 plot the data 
 >plt.figure(figsize=(16,6))
 >sns.lineplot(data=fifa_data)
