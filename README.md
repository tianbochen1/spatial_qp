# spatial_qp
Spatial Quantile periodogram

To obtain a more complete view of the spectral features of spatial data, we propose a spatial quantile periodogram (SQP) based on quantile regression with trigonometric basis functions. Compared with the ordinary spatial periodogram (SPG), the SQP describes frequency-domain behavior at different quantile levels and provides a broader picture of spatial dependence across the marginal distribution. We establish its large-sample properties and develop a Fisher-type test for periodicity. Simulations show that the SQP is more robust to contamination and detects hidden periodicities missed by the SPG. Real-data applications, including corduroy and linen textures from KTH-TIPS2-b and the Brodatz D94 brick-wall texture, demonstrate that the SQP provides richer frequency-domain information than the SPG.


The corduroy and linen images are available from the KTH-TIPS2-b
database at https://www.csc.kth.se/cvap/databases/kth-tips/.
The Brodatz D94 brick-wall image (image 1.1.12) is available from
the USC-SIPI image database at
https://sipi.usc.edu/database/database.php?volume=textures&image=12.

Run "experiment1.r", "experiment2.r", "realdata1.r", and "realdata2.r" to reproduce all the results in the paper.
