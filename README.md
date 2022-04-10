# DPOAEs-HOSA
A project to analyse DPOAEs after discotheque exposure using bispectrum.

## Abstract
In this work, **HOSA (Higher Order Spectral Analysis)** is used to analyze **DPOAEs (Distortion Product Otoacoustic Emissions)** with the aim of identifying any slight change in cochlear functionality after exposure to discotheque music.

Otoacoustic Emissions (OAEs) have a great potential to detect the earlier signs of hearing impairment.
The study concerns the analysis of DPOAEs: emissions elicited by means of two simultaneous sine tones with different frequencies identified by precise relations. The cochlear response to these stimuli is non-linear.

Preliminary analysis on otoacoustic emissions has shown promising results, for this reason we have focused on the study of DPOAEs using HOSA and mainly the bispectum, a technique already applied on other OAEs but not yet used on this kind of data. No study so far has examined use of HOSA on DPOAEs. The set of data analysed in this thesis is provided by a German study, carried out by _Jorg Muller_, _Susanne Dietrich_ e _Thomas Janssen_ [1], in which the effects induced by exposure to high level discotheque music throughout the analysis of DPOAEs before and after exposure was investigated. In the afore mentioned study, the hearing threshold was extrapolated by the linearization of DPOAEs with a model of linear regression. A limitation of the previous study is the inability to highlight the characteristic nonlinear components of DPOAEs. Our approach, on the contrary, allows the analysis of nonlinear components of the signal without compromising the content.

Starting from the set of data collected by the German team, our group programmed using Matlab R2018a some algorithms based on HOSA to extract linear and nonlinear components from the study of the bispectrum of the signals given. Two principal methods are used to analyze the dataset: the power spectrum and the bispectrum. The power spectrum showed the position and the power of the thresholds, while the bispectrum, which is the function used to extract sensitive parameters from the otoacoustic emissions, allowed the detection of the components originated from frequencies coupling that demonstrate the nonlinearity of the signal. This type of information is important to detect any possible subtle, sub-clinical damage. The study of the signals before and after noise exposure subsequently allowed to compare the results obtained investigating on possible indicators of cochlear damage. All the parameters of the bispectrum mentioned on literature were implemented [2], but only some of them turned out to be significant for a comparison before and after exposure. This work is enriched by the analysis of the bispectrum only at the specific frequencies of the two regions of interest, defined as _focus regions_: the pure tone threshold area and the DPOAEs area. This further analysis confirmed the results, showing the patterns of phase couplings. The data collected was submitted to statistical analysis and the results actually showed a reduction of the distortion products of the otoacoustic emissions. These conclusions allowed us to validate the previous study and to prove that HOSA is a valid method for analyzing DPOAEs and for diagnosing in a more objective and sensitive way possible cochlear damage due to discotheque music exposure.

[1] Müller, Jörg, Susanne Dietrich, and Thomas Janssen. "Impact of three hours of discotheque music on pure-tone thresholds and distortion product otoacoustic emissions." The Journal of the Acoustical Society of America 128.4 (2010): 1853-1869.

[2] Chua, Kuang Chua, et al. "Application of higher order statistics/spectra in biomedical signals—A review." Medical engineering & physics 32.7 (2010): 679-689.
