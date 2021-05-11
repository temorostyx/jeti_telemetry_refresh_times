# jeti_telemetry_refresh_times
Jupyter notebook for evaluation of Jeti TX logfiles with respect to refresh times of individual telemetry values
This notebook reads logfiles from Jeti Duplex transmitters
Provide the logfile to be analysed in the same folder as the notebook and assign the filename to variable logfile in cell 3
Run all cells in order of appearance
Obtained output at location/folder of the notebook:
- simplified logfile (txt) containing only actual time series data
- Excel file listing all sensors and their corresonding values with names, ids & units
- Excel file containing time series data of all sensor values including refresh times
- Excel file containing statistic measures for resfresh time distributions of individual sensor values
- png image with visual representation of refresh time distributions of individual sensor values
