# Rental Bike Analysis

This repository analyzes rental bike rides in munich from the year 2021. For more information see the heading _Dataset "Rides on the MVG bike"_ below.

## Requirements

* Python 3.7 (it was tested with this version, but probably new versions also work) 

## Getting started

(Optional) Download the dataset. The dataset is shipped with the repository, so you can skip this step.

    wget https://www.mvg.de/dam/mvg/services/mobile-services/mvg-rad/fahrten-csv/MVG_Rad_Fahrten_2021.zip

Unzip the dataset.

    unzip MVG_Rad_Fahrten_2021.zip

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