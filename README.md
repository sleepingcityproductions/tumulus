# Tumulus
### Automated discovery of burial mounds (tumuli) on Lidar scans

This jupyter notebook uses the circular and elliptical hough transformation example from the scikit-image library to the automated detection of ancient burial mounds on Lidar scans. The work is inspired by discussions with a close friend, who is an archaeologist. He thinks that those burial mounds were used as waypoints for trade routes in the past. The image analyzed in this work is taken from https://www.denkmalpflege-bw.de/geschichte-auftrag-struktur/archaeologische-denkmalpflege/prospektion/

The basic idea is simple: As these burial mounds are round objects of similar size, it should be easy to extract them from Lidar images by applying the circular hough transformation. Applying this algorithm to a large number of scans should give us several candidates although the rate of false-positives could be potentially high.
