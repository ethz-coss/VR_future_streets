# VR_future_streets

Data repository for VR experiment for future street scenarios

## Short description of folders
+ *processed_data* contains all the data for running the analysis in scripts:
    + */timeseries* contains the raw timeseries without preprocessing
    + */timeseries_1s_v2_interp1d_lin* contains used timerseries, resampled at 1s with linear interpolation.
    + */timeseries_HR_raw* contains specific raw timerseries for Heart Reate analysis.
    + *timestamps_unix.csv* contains the manually anotated timestamps for each of the sessions and tasks to synchornize and crop the raw timeseries data.
    + *short_summary_data_\** contain different aggregation of already preprocessed timeseries and experiment results to perform statistical analysis.
    + *data_HR_freq_analysis\** contain the preprocessed Heart Rate timeseries in *jasv_generate_summary_sessions_v0.70.ipynb* (apt. 3) to be used in *heart_rate.ipynb*.

+ *scripts* contains Jupyter Notebooks:
    + to explore the gathered data (*jasv_data_timeseries_exploration.ipynb*), 
    + process all the data including analysis, stats and plotting (*jasv_generate_summary_sessions_v0.70.ipynb*),
    + and detailed analysis of heart rate spectral analysis (*heart_rate.ipynb*)

+ *videos* contains examples of the recordings shown to participants in the experiment to explain the scenarios, in both informational treatments:
    + sequential (*ABC_3.MP4*)
    + parallel (*A-C-B.mp4*)