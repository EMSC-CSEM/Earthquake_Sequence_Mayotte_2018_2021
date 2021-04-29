
# Earthquake sequence in Mayotte between May 10th 2018 and April 2021

## Introduction

Since May 13th, 2018, a serie of shallow (less than 30 km depth) earthquakes have been recorded near the Mayotte Island with magnitudes up to 5.8.
The interest in studying this sequence lies in the possibility to attain a better understanding of the impacts that earthquakes have on a society where a seismological culture has not been fully developed. This dataset contains the earthquake collected by the European-Mediterranean Seismological Centre  (EMSC) through its contributors with the number of felt reports collected from eyewitnesses via the LastQuake mobile application and EMSC's web sites. The main interest of this dataset is the association of seismological data with reports from the population.


## Data Collection

The earthquake data regroups data collected by the EMSC between May 10th, 2018 and the end of April 2021 in the region delemited by longitudes between 42 and 48 and latitudes between -16 and -10. Contributors of the EMSC are composed of more than 80 national seismic instituts which send their data in real time. During this period, the among of contributors for earthquakes in the Mayotte region has evolved in time. At the begining of the crisis, the EMSC has received data only from global networks that only detect earthquakes with magnitude greater than 4 in this region. Then the BRGM has provided more complete data and it was then possible to add smaller seismic events that were felt by the population. Finally, in 2019, earthquake information in Mayotte were available on the RENASS website and the EMSC began to access the complete catalogue of the seismicity near Mayotte.

Moreover this seismic crisis has been widely felt by the population and the EMSC has collected a lot of reports. This dataset contains also the total number of felt reports associated to each earthquake.


## Dataset

### mayotte_eq.csv

The file  mayotte_eq.csv contains the information of seleted earthquakes. Each row corresponds to one earthquake information separated by a comma and the first row defines the field headers.
 1. evid : EMSC event identifier. The corresponding url to retrieve earthquake information is https://www.emsc-csem.org/Earthquake/earthquake.php?id=EVID where EVID is the evid number (e.g. 665884).
 2. mag : magnitude of the earthquake
 3. t0 : origin time of the earthquake in UTC. The format is "year-month-day hours:minutes:seconds"
 4. lon : longitude of the epicenter
 5. lat : latitutde if the epicenter
 6. feltreport : number of felt reports collected for this event.

