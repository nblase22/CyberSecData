# CyberSecData

!([Cybersecurity Image] https://3b6xlt3iddqmuq5vy2w0s5d3-wpengine.netdna-ssl.com/state-of-security/wp-content/uploads/sites/3/shutterstock_609173918-800x450.jpg)

The programs contained herein create a machine learning model that predicts a login's success or failure based on Source User Domain, Logon Type, and Authentication Orientation.

The data set can be found here:
[a link] (https://csr.lanl.gov/data/cyber1/)

The set used is auth.txt.gz

Due to computer memory resource issues, the above data file was split into 3 separate CSV files.
* auth10k.csv (first 10k rows of the datafile)
* auth50k.csv (first 50k rows of the datafile)
* auth100k.csv (first 100k rows of the datafile)
          
When running the model creator, uncomment the lines of code corresponding to the datafile you prefer to use.
          

The program has the following requirements:
* Pandas
* Os
* Sklearn
* Keras
* Tensorflow
