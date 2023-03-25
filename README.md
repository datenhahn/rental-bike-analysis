# Rental Bike Analysis

This repository analyzes rental bike rides in munich from the year 2021. For more information see the heading _Dataset "Rides on the MVG bike"_ below.

It is the accompanying repository to this blog post which discusses the findings: https://medium.com/@jonas.hahn/riding-the-data-wave-insights-into-munichs-bike-rental-trends-8330bc4e6c41

The data is prepared for analysis and the following questions are answered:

* How long do people usually rent these bikes?
* How far do they travel with them?
* Do people often use them complementary to the other public transport?

## Requirements

* Python 3.7 (it was tested with this version, but probably new versions also work)

### Libraries used

The following python libraries were used. (see `requirements.txt`)

    jupyter==1.0.0
    pandas==1.5.3
    matplotlib==3.7.1
    geopy==2.3.0
    numpy==1.24.2
    black==23.1.0
    jupyter_black==0.3.3

## File Description

* `rental-bike-analysis.ipynb` : Jupyter Notebook containing the data analysis.  
* `MVG_Rad_Fahrten_2021.zip` : 2021 MVG rental bike data (zipped).   



## Getting started

(Optional) Download the dataset. The dataset is shipped with the repository, so you can skip this step.

    wget https://www.mvg.de/dam/mvg/services/mobile-services/mvg-rad/fahrten-csv/MVG_Rad_Fahrten_2021.zip

Unzip the dataset.

    unzip MVG_Rad_Fahrten_2021.zip

Install requirements.

    pip install -r requirements.txt

Start the jupyter notebook.

    jupyter

Now open in a browser: http://localhost:8888/notebooks/rental-bike-analysis.ipynb

## Dataset "Rides on the MVG bike"

https://opendata.muenchen.de/dataset/fahrten-mit-dem-mvg-rad

This data record includes anonymized raw data from trips with MVG bikes. The following data can be downloaded, viewed and evaluated for each bike rental:

* Start date and time of the loan
* End date and time of the loan
* Loan start coordinates
* Coordinates rental end
* Rental start station-based or free-floating
* Possibly station name
* Rental end station based or free floating
* Possibly station name

The data is always provided for an entire year. The upload takes place with a certain time lag of about 5-6 months, so that the data is available in May or June of the following year.

## License

All code written in this repo is under the Apache License Version 2.0.

The data is under the Datenlizenz Deutschland – Namensnennung – Version 2.0 https://www.govdata.de/dl-de/by-2-0 .

Datenquelle: dl-de/by-2-0: Landeshauptstadt München – opendata.muenchen.de

https://opendata.muenchen.de/pages/nutzungsbedingungen