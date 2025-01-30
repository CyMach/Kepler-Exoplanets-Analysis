# Kepler-Exoplanets-Analysis

***Scattered throughout countless galaxies, challenge the notion that we are alone in the universe.***

-->Exoplanets are the worlds that exist outside of our solar system.

-->Also known as extrasolar planets, these bodies often orbit their own stars with some being part of entire planetary systems.

-->Exoplanets are made out of the same elements as the world’s and our solar system, based on their composition and structure are just as diverse varying atmospheric density and gravity.

**Classifications**

-->Neptune like planets large gaseous worlds 

Ex.: HAT P26B

-->Hot Jupiter | Closely orbit stars causing high temperatures 

Ex.: WASP 18B

-->Super Earth | Smaller than gas giants larger than earth, Super earths are terrestrial made primarily of rocky or icy material  

Ex.: 555 Cancer B

-->Earth Analog | Similar to earth in size, composition and distance to their home star

**Dataset**

*This dataset is a cumulative record of all observed Kepler "objects of interest" — all of the approximately 10,000 exoplanet candidates Kepler has taken observations on.*

This dataset has an extensive data dictionary with 49 attributes, Highlightable columns of note are :

Identification

Kepid Target identification number, as listed in the Kepler Input Catalog.

Disposition

koi_disposition values are CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED

Transit Properties

koi_score A value between 0 and 1 that indicates the confidence in the KOI disposition. 

koi_period  The interval between consecutive planetary transits.

Threshold-Crossing Event Information

koi_model_snr Transit depth normalized by the mean uncertainty in the flux during the transits.

koi_num_transits The number of expected transits or partially-observed transits associated with the planet candidate occurring within the searched light curve. This does not include that fall completely within data gaps.

![image](https://github.com/user-attachments/assets/dff6b690-dbc4-4025-8c40-8de0b3f1c917)

**Classification models used**

-->Naive Bayes

-->Support Vector Machine

-->Decision Tree

-->Neural Network

-->Gaussian Mixture Model

-->Random Forest

-->AdaBoost

-->XGBoost


