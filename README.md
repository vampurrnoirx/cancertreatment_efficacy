# cancertreatment_efficacy
This project analyzes five real-world neuroscience and behavioral datasets, applying bootstrapped confidence intervals and permutation-based hypothesis testing to quantify uncertainty, evaluate treatment effects, and rigorously assess the strength of statistical evidence. By integrating advanced statistical methods with practical questions in neuroscience and behavior, the project seeks to bridge the gap between technical analysis and meaningful, human-centered insight.

Approaches

1. Chloroquine & Glioblastoma: Estimates the effect of chloroquine on glioblastoma cell growth using a 95% bootstrapped confidence interval, then confirms statistical significance via permutation test. Results suggest chloroquine reduces the average cell count by approximately 521–742 cells relative to control.
2. Birthweight in North Carolina: We construct a confidence interval for the mean birthweight of newborns in North Carolina based on a random sample of 800 state birth records. This approach allows us to critically evaluate which population-level averages are plausible given the observed data, providing a more nuanced understanding of birthweight variation within the state.
3. Dog Pawedness & Owner Handedness Tests whether a dog’s paw preference is associated with its owner’s handedness by estimating the difference in right-pawedness proportions across groups.
4. Hippocampal Atrophy in Epilepsy Estimates and tests the slope of ipsilateral and contralateral hippocampal volume change over years since diagnosis, revealing lateralized atrophy concentrated on the seizure-origin side.
5. Infant Face Perception, Phantom Limb Pain & The Dress: Three permutation tests evaluating innate face recognition in one-month-old infants, the efficacy of mirror-tracing therapy for phantom limb pain, and the role of shadow perception in color-illusion reports.

Tools & Skills

R · ggplot2 · dplyr · infer · moderndive · bootstrapping · confidence intervals · permutation testing · hypothesis testing · data visualization
