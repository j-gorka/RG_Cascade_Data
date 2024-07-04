## Summary
This repository contains a >62 million sample cascading blackout dataset, consisting of blackout simulations for all N-2 initial outages, across a year's worth of hourly load/generation profiles on the RTS-GMLC test case. The dataset was created for use in our paper "Cascading Blackout Severity Prediction with Statistically-Augmented Graph Neural Networks" which was presented at the 2024 Power Systems Computation Conference in Paris, FR. If you use this dataset, we would appreciate the citation of this paper.

If you have further questions, feel free to reach out to jgorka[at]wisc.edu

## Contents
ac_2020/: Hourly RTS-GMLC load/generation profiles in MATPOWER format, generation/loading info. in CSV format, and DCSIMSEP blackout simulator results for all load/gen profiles and all N-2 initial outage combinations (in CSV format).

ac_july_real/: Smaller dataset with same contents, consisting of only load/generation profiles for the month of July.


