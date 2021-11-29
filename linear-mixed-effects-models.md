---
title: Linear mixed-effects models in R, and a new tool for data simulation
tags: statistics, variance, regression, ANOVA, tutorial, lme4, R, rstats
---


## Linear mixed-effects models in R, and a new tool for data simulation
<br>

**Pablo Bernabeu**
<br>

Lancaster University, 26 Nov 2020

---

## Rationale

- Earlier, weaker computers
    - Hence, aggregation (or downsampling) across trials, items, measurement channels (e.g., EEG), etc

- Now, computational power
    - Multi-core laptops, High-Performance (or High-End) Computing clusters

<div style='margin-bottom:25px'></div>

:::info
<div style="text-align:left; margin-top:5px; padding-bottom:11px; padding-left:45px;"> 
<span  style="font-size:70%"> Singmann and Kellen (2019) </span> 
</div>
:::

---

## *Rationale* --- independence assumption

- Accounting for variation within factors with multiple observations, such as participants, trials, items, channels, etc 
    - Earlier: F1 and F2 ANOVAs (Clark, 1973) 

<div style='margin-bottom:35px'></div>

:::info
<div style="text-align:left; margin-top:5px; padding-bottom:11px; padding-left:45px;"> 
<span  style="font-size:70%"> Brauer and Curtin (2018), Brown (2020), Meteyard and Davies (2020), Singmann and Kellen (2019) </span> 
</div>
:::

---

## *Rationale* --- statistical precision

- Less unexplained variance = more precision --> more power
    - Lower Type II error rate (false negatives) without increasing Type I error rate (false positives)

<div style='margin-bottom:35px'></div>

:::info
<div style="text-align:left; margin-top:5px; padding-bottom:11px; padding-left:45px;"> 
<span  style="font-size:70%"> Brauer and Curtin (2018), Brown (2020), Meteyard and Davies (2020), Singmann and Kellen (2019) </span> 
</div>
:::

---

## *Rationale* --- theoretical accuracy

In addition to statistical assumptions, linear mixed-effects models help uphold theoretical assumptions about the generalisability of findings (Yarkoni, 2020).

---

## Robustness
 
- Quite robust to assumption violations (Schielzeth et al., 2020)

---

### Random effects (intercepts and slopes)

Visualise fixed regression and the three variations of random effects.

[![Types of random effects](https://bookdown.org/steve_midway/DAR/images/07_models.png =430x300)](https://bookdown.org/steve_midway/DAR/random-effects.html)

<div style="font-size:60%; font-family:courier;">
    
Image source: Midway (2021), https://bookdown.org/steve_midway/DAR/random-effects.html

</div>

---

- R code structure:

    <div style="font-size:60%; font-family:courier;">
    + (effect | highest_level / lower_level / lowest_level)
    </div>

- Minimum five or six levels in nesting factor 
    (Bolker, 2015; Singmann & Kellen, 2019)

---

### Random intercepts and slopes

- [Singmann and Kellen (2019)](http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf) - see Table 2.

<div style='margin-bottom:35px'></div>

:::info
<div style="text-align:left; margin-top:5px; padding-bottom:11px; padding-left:45px;"> 
<span  style="font-size:70%"> Barr et al. (2013) </span> 
</div>
:::

---

### Fixed effects

- [Singmann and Kellen (2019)](http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf) - see Table 1.

---

### Convergence challenges

- Approach: Prioritising conservativeness

    - [Brauer and Curtin (2018)](https://psych.wisc.edu/Brauer/BrauerLab/wp-content/uploads/2014/04/Brauer-Curtin-2018-on-LMEMs.pdf) - see Table 17.

    - [Singmann and Kellen (2019)](http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf) - see fragment from 'As a first step, it seems advisable to remove the correlations among random slopes'.

---

### Convergence challenges

- Approach: Prioritising conservativeness

    - [Singmann and Kellen (2019)](http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf) - see fragment from 'When fitting mixed models with complicated random effects structures, convergence warnings appear frequently.'

    - [Brown (2020)](https://doi.org/10.31234/osf.io/9vghm) - see fragment from 'The one I recommend starting with is changing the optimizer'.

---

### Convergence challenges

- Approach: Remaining conservative without losing power

    - [Matuschek et al. (2017)](https://doi.org/10.1016/j.jml.2017.01.001)

---

### Effect size

- Standardised effect sizes are tricky due to random effects structure (Piepho, 2019).

- [Lorah (2018)](https://link.springer.com/article/10.1186/s40536-018-0061-2) offers options for fixed and random effects.

- see also [Singmann and Kellen (2019)](http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf) - section 'Effect Sizes For Mixed Models'.

---

### *p* values

- [Luke (2017)](https://doi.org/10.3758/s13428-016-0809-y) - Kenward-Roger or Satterthwaite methods the most robust

- [Singmann and Kellen (2019)](http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf) - afex::mixed()

---

### Other resources

- Tutorials
<span style='font-size:60%;'>
    - https://bbolker.github.io/morelia_2018/notes/mixedlab.html
    - https://mac-theobio.github.io/QMEE/Mixed_models_examples.html
    - https://cran.r-project.org/web/packages/afex/vignettes/afex_mixed_example.html
</span>

---

### Other resources

- Packages
<span style='font-size:60%;'>
    - https://cran.r-project.org/package=lme4
    - https://cran.r-project.org/web/packages/afex/afex.pdf
    - https://cran.r-project.org/web/packages/lmerTest/lmerTest.pdf
    - http://www.strengejacke.de/sjPlot/index.html
</span>

---

### On a different note, a new tool for data simulation

- Bernabeu and Lynott (2020)
<span style='font-size:60%;'>
    - https://github.com/pablobernabeu/Experimental-data-simulation/
</span>

---

#### References (1/3)

<div style="font-size:50%; text-align:left; text-indent:-2em; margin-left:2em;">

Barr, D. J., Levy, R., Scheepers, C., & Tily, H. J. (2013). Random effects structure for confirmatory hypothesis testing: Keep it maximal. *Journal of Memory and Language, 68*, 255–278. http://dx.doi.org/10.1016/j.jml.2012.11.001

Bernabeu, P., & Lynott, D. (2020). *Web application for the simulation of experimental data* (Version 1.2). https://github.com/pablobernabeu/Experimental-data-simulation/

Bolker, B. M. (2015). Linear and generalized linear mixed models. In G. A. Fox, S. Negrete-Yankelevich, & V. J. Sosa (Eds.), *Ecological statistics: Contemporary theory and application*. Oxford, UK: Oxford University Press.

Brauer, M., & Curtin, J. J. (2018). Linear mixed-effects models and the analysis of nonindependent data: A unified framework to analyze categorical and continuous independent variables that vary within-subjects and/or within-items. *Psychological Methods, 23*(3), 389–411. https://psych.wisc.edu/Brauer/BrauerLab/wp-content/uploads/2014/04/Brauer-Curtin-2018-on-LMEMs.pdf

Brown, V. A. (2020). *An introduction to linear mixed effects modeling in R.* PsyArXiv. https://doi.org/10.31234/osf.io/9vghm

</div>

---

#### References (2/3)

<div style="font-size:50%; text-align:left; text-indent:-2em; margin-left:2em;">

Clark, H. H. (1973). The language-as-fixed-effect fallacy: A critique of language statistics in psychological research. *Journal of Verbal Learning and Verbal Behavior, 12*(4), 335-359. https://doi.org/10.1016/S0022-5371(73)80014-3

Lorah, J. (2018). Effect size measures for multilevel models: definition, interpretation, and TIMSS example. *Large-scale Assessments in Education, 6*, 8. https://doi.org/10.1186/s40536-018-0061-2

Luke, S. G. (2017). Evaluating significance in linear mixed-effects models in R. *Behavior Research Methods, 49*(4), 1494–1502. https://doi.org/10.3758/s13428-016-0809-y

Matuschek, H., Kliegl, R., Vasishth, S., Baayen, H., & Bates, D. (2017). Balancing type 1 error and power in linear mixed models. *Journal of Memory and Language, 94*, 305–315. https://doi.org/10.1016/j.jml.2017.01.001

Meteyard, L., & Davies, R. A. (2020). Best practice guidance for linear mixed-effects models in psychological science. *Journal of Memory and Language, 112*, 104092. https://doi.org/10.1016/j.jml.2020.104092

</div>

---

#### References (3/3)

<div style="font-size:50%; text-align:left; text-indent:-2em; margin-left:2em;">

Piepho, H.‐P. (2019). A coefficient of determination (*R*<sup>2</sup>) for generalized linear‐mixed models. *Biometrical Journal, 61*, 860–872. https://doi.org/10.1002/bimj.201800270

Schielzeth, H., Dingemanse, N. J., Nakagawa, S., Westneat, D. F., Allegue, H, Teplitsky, C., Reale, D., Dochtermann, N. A., Garamszegi, L. Z., & Araya-Ajoy, Y. G. (2020). Robustness of linear mixed-effects models to violations of distributional assumptions. *Methods in Ecology and Evolution, 00*, 1– 12. https://doi.org/10.1111/2041-210X.13434

Singmann, H., & Kellen, D. (2019). An Introduction to Mixed Models for Experimental Psychology. In D. H. Spieler & E. Schumacher (Eds.), *New Methods in Cognitive Psychology* (pp. 4–31). Hove, UK: Psychology Press. http://singmann.org/download/publications/singmann_kellen-introduction-mixed-models.pdf

Yarkoni, T. (2020). The generalizability crisis. *Behavioral and Brain Sciences*, 1-37. https://doi.org/10.1017/S0140525X20001685

</div>