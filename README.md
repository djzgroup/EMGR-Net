# Weather-aware Multi-granularity Representation Learning for Cross-view Geo-Localization under Adverse Conditions

This work targets robust cross-view geo-localization where ground-view images are matched to aerial or satellite imagery under complex weather and appearance changes. We propose a weather-aware multi-granularity framework that jointly learns:

- A global branch with weather-aware modulation guided by predicted weather cues  
- A geometry-aware local branch with multi-receptive field convolutions and axial context attention  
- A latent category branch that aggregates region features into self-discovered scene prototypes

A physics-inspired weather domain augmentation strategy simulates realistic weather-induced degradations during training and provides supervision for weather-aware representation learning. The network is optimized with a multi-granularity contrastive objective over global, local and latent representations.

Experiments on CVUSA, CVACT and VIGOR show consistent gains over recent state-of-the-art methods, especially for cross-area and cross-dataset generalization under challenging weather conditions.

Code: coming soon.
