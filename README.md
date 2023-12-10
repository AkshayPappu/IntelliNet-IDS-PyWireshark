# IntelliNet-IDS-PyWireshark
Intelligent network intrusion detection with Wireshark and Python. A hybrid anomaly detection 
approach for application classification and network packet analysis.

***Usage instructions***
1. Conduct packet analysis in wireshark and preprocess that data into a csv

2. Run the ApplicationClassifierPackets.ipynb script with your dataset as the input file. 
A new processed dataset will be created in the py_input_files directory, which you can use as
the input to the ApplicationFilter.ipynb script.

3. Run the ApplicationFilter.ipynb script in order to create separate datasets based on the application. 
These new datasets will be placed in the py_input_files directory

4. Run the PAD_Pipeline.ipynb script with the application dataset of your choice. Visualize the output with
the library of your choice. 
