# Code for "Minimising missed and false alarms: a vehicle spacing based approach to conflict detection"

This work is accepted and going to be presented at the 35th IEEE Intelligent Vehicles Symposium. The approach this paper is proposing is still under refinement and currently not mature enough for general applications. Hopefully I'll make it a success and soon open-source a more complete approach :)

## Abstract
Safety is the cornerstone of L2+ autonomous driving and one of the fundamental tasks is forward collision warning that detects potential rear-end collisions. Potential collisions are also known as conflicts, which have long been indicated using Time-to-Collision with a critical threshold to distinguish safe and unsafe situations. Such indication, however, focuses on a single scenario and cannot cope with dynamic traffic environments. For example, TTC-based crash warning frequently misses potential collisions in congested traffic, and issues false alarms during lane-changing or parking. Aiming to minimise missed and false alarms in conflict detection, this study proposes a more reliable approach based on vehicle spacing patterns. To test this approach, we use both synthetic and real-world conflict data. Our experiments show that the proposed approach outperforms single-threshold TTC unless conflicts happened in the exact way that TTC is defined, which is rarely true. When conflicts are heterogeneous and when the information of conflict situation is incompletely known, as is the case with real-world conflicts, our approach can achieve less missed and false detection. This study offers a new perspective for conflict detection, and also a general framework allowing for further elaboration to minimise missed and false alarms. Less missed alarms will contribute to fewer accidents, meanwhile, fewer false alarms will promote people's trust in collision avoidance systems. We thus expect this study to contribute to safer and more trustworthy autonomous driving.

## Package requirements
`jupyter notebook`, `numpy`, `pandas`, `tqdm`, `glob`, `matplotlib`, `scipy`
