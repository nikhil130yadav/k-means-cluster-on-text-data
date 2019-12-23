# k-means-cluster-on-text-data
This repository explains how to make use of k-means algorithm to make clusters of similar/related words.

Example of data is below:
words with respective vectors

"was 0.086888 -0.19416 -0.24267 -0.33391 0.56731 0.39783 -0.97809 0.03159 -0.61469 -0.31406 0.56145 0.12886 -0.84193 -0.46992 0.47097 0.023012 -0.59609 0.22291 -1.1614 0.3865 0.067412 0.44883 0.17394 -0.53574 0.17909 -2.1647 -0.12827 0.29036 -0.15061 0.35242 3.124 -0.90085 -0.02567 -0.41709 0.40565 -0.22703 0.76829 0.60982 0.070068 -0.13271 -0.1201 0.096132 -0.43998 -0.48531 -0.5188 -0.3077 -0.75028 -0.77 0.3945 -0.16937

said 0.38973 -0.2121 0.51837 0.80136 1.0336 -0.27784 -0.84525 -0.25333 0.12586 -0.90342 0.24975 0.22022 -1.2053 -0.53771 1.0446 0.62778 0.39704 -0.15812 0.38102 -0.54674 -0.44009 1.0976 0.013069 -0.89971 0.41226 -2.2309 0.28997 0.32175 -0.72738 -0.092244 3.028 -0.062599 0.038329 0.0072918 -0.35388 -0.92256 0.097932 0.10068 1.2116 0.88233 -0.46297 1.3186 0.32705 -0.73446 0.89301 -0.45324 -1.2698 0.86119 0.1415 1.2018"

output is in the form:

Cluster 72 :: car|cars|vehicles|vehicle|truck|trucks
Cluster 73 :: zagreb|ossetia|pristina|abkhazia|tbilisi|baku|tirana|nicosia|skopje|mostar|fk
Cluster 74 :: guangdong|zhejiang|shandong|jiangsu|henan|liaoning|hunan|hebei|shanxi|anhui|hubei
Cluster 75 :: iraqis|afghans|iranians|pakistanis|saudis

Using this code you can control number of words to be fed to K-means algorith as sometimes there are memory constraints and
also you can control number of clusters to be created using reduction factor.

