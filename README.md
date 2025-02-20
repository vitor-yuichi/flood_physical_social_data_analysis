Data Documentation 🚀🐍


The data processing was mainly performed using Jupyter Notebooks on Google Colab (Python). 

Files Overview
This section provides descriptions of the various data files used in this study.

1. Tweets Data
These CSV files contain tweet data extracted from the study area for different months:

812A_2019_JAN_2KM.csv: Tweets collected in the study area for January 2019.
812A_2019_FEV_2KM.csv: Tweets collected in the study area for February 2019.
812A_2019_MAR_2KM.csv: Tweets collected in the study area for March 2019.
2. Flood Data
These files contain flood data corresponding to specific rain gauges:

812A_alag.csv: Flood data related to the 812A rain gauge.
833A_alag.csv: Flood data related to the 833A rain gauge.
857A_alag.csv: Flood data related to the 857A rain gauge.
Alagamentos_2019.csv: Raw flood data extracted for the entire year of 2019.
3. Other Data
Additional data files used for analysis:

boxplot.csv: Data used for generating word frequency boxplots.
data1.csv, data2.csv, data3.csv: Raw rainfall gauge data for the 812A, 833A, and 857A stations, corresponding to January, February, and March 2019, respectively.
4. Main Processed Data
MainDataProcessed.csv: Aggregated results on a daily basis. The file includes the following columns:
words_fr_812|833|857: Word frequencies from the tweets for each corresponding station.
tw_833|812|857: Tweet frequencies for the corresponding stations.
floods_812|833|857: Flood data for the corresponding stations.
gauge_812|833|857: Rainfall gauge data for the corresponding stations.
5. Radar Data
radar_2019.csv: Raw radar data for the year 2019.
