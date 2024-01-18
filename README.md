The data analysis includes:
- descriptive statistics
- correlation matrix
- clustering:
  - K Means
  - X Means
  - DB Scan
  - Hierarchical
- classification: 
  - Decision tree
  - Random forest
  - K-Nearest Neighbors
  - Support vector machines
- Pattern mining

The dataset reviewed contains data from 2126 measurements extracted from cardiotocographs and graded by experienced obstetricians, as described in: Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318.

Cardiotocography (CTG) is a simple and cost-effective option for assessing the health of the fetus, allowing health professionals to intervene to prevent infant and maternal mortality. The equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.

- baseline value FHR baseline (beats per minute)
- accelerations Number of accelerations per second
- fetal_movement Number of fetal movements per second
- uterine_contractions Number of uterine contractions per second
- light_decelerations Number of light decelerations per second
- severe_decelerations Number of severe decelerations per second
- prolongued_decelerations Number of prolonged decelerations per second
- abnormal_short_term_variability Percentage of time with abnormal short-term - variability
- mean_value_of_short_term_variability Average value of short-term variability
- percentage_of_time_with_abnormal_long_term_variability Percentage of time with abnormal long term variability
- mean_value_of_long_term_variability Average value of long-term variability
- histogram_width Width of the FHR histogram.
- histogram_min Minimum (low frequency) of the FHR histogram
- histogram_max Maximum (high frequency) of the FHR histogram
- histogram_number_of_peaks Number of histogram peaks
- histogram_number_of_zeroes Number of zeros of the histogram
- histogram_mode Fashion of the histogram
- histogram_mean Mean of the histogram
- histogram_median Median of the histogram
- histogram_variance Variance of the histogram
- histogram_tendency Tendency of the histogram

Target: fetal_health Marked as 1 (Normal), 2 (Suspicious) and 3 (Pathological)
