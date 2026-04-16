# Analysis of TRPM8 Inhibitor (AMTB) Effects on Lipid Droplets in 3T3-L1 Adipocytes

This project looks at how different concentrations of the TRPM8 inhibitor AMTB affect lipid droplets in 3T3-L1 adipocytes. The analysis is based on measurements from confocal images, using Area, Perimeter, Integrated Density (IntDen), and Raw Integrated Density (RawIntDen).

---

## Results

### Lipid Droplet Morphology (Area and Perimeter)

At the highest concentration (10 μM), lipid droplet size is lower compared to control and lower doses. Both area and perimeter decrease, which suggests smaller droplets at this concentration.

For intermediate doses (1–5 μM), the trend is not very clear. Some groups, especially 5 μM, show a lot of variation and even slight increases in some values. So the response does not seem strictly linear.

The 0.5 μM group is quite similar to control, which suggests that this concentration may not be enough to produce a noticeable effect.

---

### Lipid Content (Integrated Density and Raw Integrated Density)

Integrated density values also change with dose. The 10 μM group has the lowest values, which suggests reduced lipid content.

At the same time, some intermediate doses (like 3 μM and 5 μM) show higher values than control. This makes the pattern a bit inconsistent and possibly indicates a more complex response.

Raw integrated density follows a similar trend.

---

## Statistical Analysis

The data does not satisfy the assumptions required for standard parametric tests.
Shapiro–Wilk tests show that the data is not normally distributed, and Levene’s test shows unequal variances.

Because of this, non-parametric tests were used.

The Kruskal–Wallis test shows significant differences across all groups (p << 0.001), so AMTB concentration does affect lipid droplet features.

Dunn’s post hoc test shows that most of the significant differences involve the higher doses, especially 5 μM and 10 μM.

ANOVA and Tukey HSD were also run for comparison. Even though the assumptions are not fully met, the overall trends are similar.

---

## Summary Statistics

### Area

| Group   | Mean ± SD   | N    |
| ------- | ----------- | ---- |
| Control | 2.06 ± 1.90 | 859  |
| 0.5 μM  | 2.03 ± 2.14 | 734  |
| 1 μM    | 1.70 ± 1.53 | 779  |
| 3 μM    | 2.00 ± 2.05 | 764  |
| 5 μM    | 1.81 ± 2.37 | 1098 |
| 10 μM   | 1.45 ± 1.69 | 644  |

Area generally decreases with increasing concentration, with the lowest value at 10 μM. The 5 μM group shows the highest variability.

---

### Perimeter

| Group   | Mean ± SD   | N    |
| ------- | ----------- | ---- |
| Control | 5.82 ± 2.50 | 859  |
| 0.5 μM  | 5.84 ± 2.94 | 734  |
| 1 μM    | 5.49 ± 2.53 | 779  |
| 3 μM    | 5.90 ± 2.94 | 764  |
| 5 μM    | 5.41 ± 3.06 | 1098 |
| 10 μM   | 5.03 ± 2.72 | 644  |

Perimeter follows a similar pattern. The 3 μM group is slightly higher than expected, which might be due to changes in droplet shape rather than size alone.

---

### Integrated Density

| Group   | Mean ± SD         | N    |
| ------- | ----------------- | ---- |
| Control | 3512.91 ± 4563.74 | 859  |
| 0.5 μM  | 4146.58 ± 5667.80 | 734  |
| 1 μM    | 3072.39 ± 3604.19 | 779  |
| 3 μM    | 4185.30 ± 5142.39 | 764  |
| 5 μM    | 3828.33 ± 6317.55 | 1098 |
| 10 μM   | 2822.78 ± 4198.31 | 644  |

The highest mean value appears at 3 μM, while 10 μM is the lowest. There is quite a bit of variability across all groups.

---

### Raw Integrated Density

| Group   | Mean ± SD       | N    |
| ------- | --------------- | ---- |
| Control | 327427 ± 425372 | 859  |
| 0.5 μM  | 386489 ± 528277 | 734  |
| 1 μM    | 286368 ± 335935 | 779  |
| 3 μM    | 390098 ± 479306 | 764  |
| 5 μM    | 356826 ± 588838 | 1098 |
| 10 μM   | 263102 ± 391311 | 644  |

This follows the same general trend as integrated density, with higher values at intermediate doses and lower values at 10 μM.

---

## Interpretation

Overall, AMTB appears to affect both lipid droplet size and lipid content.

The clearest effect is at 10 μM, where both size and intensity decrease, suggesting reduced lipid accumulation.

The intermediate doses do not follow a simple pattern and show mixed results, which could mean the response is not linear.

---

## Conclusion

Higher concentrations of AMTB (especially 10 μM) reduce lipid droplet size and lipid content in adipocytes. Lower concentrations show weaker or less consistent effects.

These results suggest that TRPM8 may be involved in lipid storage, but more work would be needed to understand the mechanism.

---

## Notes

* The data shows high variability across all groups, which is common in biological experiments
* This could be due to biological differences between cells or limitations in image processing
