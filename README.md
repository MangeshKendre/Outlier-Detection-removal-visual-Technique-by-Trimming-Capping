# Outlier-Detection-removal-visual-Technique-by-Trimming-Capping


This repository showcases the implementation of three outlier detection and removal techniques: Technique 1 (Remove), Technique 2 (Cap), and Technique 3 (Trim). These techniques are commonly used to handle outliers in data analysis and statistical modeling.

## Techniques

1. Technique 1 (Remove):
   - Description: This technique involves identifying and removing outliers from the dataset.
   - Implementation: The implementation includes the identification of outliers using a specified criterion, such as z-scores or interquartile range (IQR), and removing the identified outliers from the dataset.

2. Technique 2 (Cap):
   - Description: This technique involves capping the outliers by replacing them with predefined upper and lower bounds.
   - Implementation: The implementation includes setting threshold values for the upper and lower bounds based on statistical measures such as z-scores or percentiles, and replacing outliers outside of these bounds with the respective bounds.

3. Technique 3 (Trim):
   - Description: This technique involves trimming the dataset by removing a certain percentage of extreme values from both ends of the distribution.
   - Implementation: The implementation includes calculating the cutoff values based on the desired trimming percentage, and removing the extreme values beyond these cutoffs from the dataset.
