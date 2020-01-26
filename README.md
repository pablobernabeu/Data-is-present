# *Data Is Present*

## Enhanced Presentation of Data through Reproducible Reports and Data Dashboards

Scientific articles are including more and more supplementary materials, ever more advanced. This has been facilitated by burgeoning technologies and available training. Another contributing factor was the replication crisis in psychology. As a result, researchers now customarily examine the data and code for studies. Standard materials such as data sets and code scripts could be referred to as Version 1.0 of open data and reproducibility. Excitingly, software developers and contributors have brought us Version 2.0 already!

Enabled by a [fellowship of the Software Sustainability Institute](https://www.software.ac.uk/about/fellows/pablo-bernabeu), this open scholarship project aims to facilitate the presentation of open-access, academic/non-academic data. The best tool for this purpose is open-source software, such as R or Python.

## Open Access Data

Data is increasingly a public good. Academics and non-academic researchers (scientists, governments, NGOs) nowadays share a lot of their data under citation-based licences (e.g., [Creative Commons](https://creativecommons.org/), the UK [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/1/), etc.). This allows any analysts to access these raw data, perform the visualisations and analyses they like, and share these.

## Open Source Software

Programs such as R and Python offer free, powerful resources for data processing, visualisation, and analysis. Experience in these programs is highly valued in data-intensive sectors of the job market.

## Activities

The ultimate activities of this project are open data hackathons. To facilitate access to this activity, introductory and intermediate workshops in R will be available for free. All activities will carried out in various cities of the UK.

### R Workshops

These are participatory, practical workshops that draw on multi-levelled examples of real code. Common challenges will be flagged, and further resources provided. Every workshop will have a taught part and a hands-on part. The level of the taught content will be largely tailored to the audience, and the hands-on part will be individually adaptable thanks to easier and tougher tasks available.

Participants will acquire or hone experience with a suite of interrelated tools based on Docker and R. The three tools--R Markdown, data dashboards, and Binder environments--are all underlain by freeware, inexpensive applications, and reproducible workflows. The usefulness of these tools extends from academia to data science. 

*Essential:* R (https://www.r-project.org/) and RStudio (https://rstudio.com/products/rstudio/download/). 

*Encouraged:* Familiarity with the relevant links herein; your own data and R code on Github. 

1. **Introduction to R**

2. **[R Markdown reports](https://rmarkdown.rstudio.com/)** —  Set your input and output beautifully in stone. These reports may be enriched with website features (HTML/CSS), and published as websites, PDF, or Word. Moreover, by using R packages such as `pagedown`, `blogdown`, `bookdown`, `flexdashboard`, reports can be turned into blogs, books, and data dashboards. 

3. **Online data dashboards (introduction)** —  The better part of this workshop covers a further step in open data: web applications used to visualise data in detail through tables and plots. These all-reproducible applications are published as websites, and therefore, can include hyperlinks and downloadable files. Users need not program. Some of the R packages used are `knitr`, `reactable`, `ggplot`, `plotly`, `rmarkdown`, `flexdashboard`, and `shiny`. The aim is to look at different forms of dashboards ([Flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) and [Shiny](https://shiny.rstudio.com/)), and the suitable platforms for online hosting (personal websites and RPubs, Binder, Shinyapps, and custom servers). A great thing: dashboards may be made very simple, but they also offer the possibility of infinite improvement by drawing on HTML, CSS, and Javascript.

4. **Online data dashboards (intermediate)** —  More advanced practice with each of the hosting possibilities (e.g., [Flexdashboard website](http://rpubs.com/pcbernabeu/Dutch-modality-exclusivity-norms), [Flexdashboard Shiny](https://pablobernabeu.shinyapps.io/Dutch-modality-exclusivity-norms/#section-table), [Shiny](https://pablobernabeu.shinyapps.io/ERP-waveform-visualization_CMS-experiment/)).

5. **Binder environments (Docker images)** —  Use virtual environments to enable public access to your data and code in RStudio, directly on the Internet, or to host web applications. We'll work through the nuts and bolts of deploying Github-based Binder environments at https://mybinder.org/, to host Rstudio instance and web applications (see https://github.com/binder-examples/r). Attendees may deploy environments and check on them by the end of the workshop.


### Hackathons

These hackathons are half day meetings meetings in which participants will collaborate to create reproducible reports (e.g., R Markdown) or data dashboards (e.g., R Shiny) from any open access data they choose.

*Essential:* Basic knowledge of dashboard development.

*Encouraged:* Familiarity with the relevant links herein; an idea about the data and analyses to be performed.

- **Data**: Academic or non-academic, open-access data from sources such as [OSF](https://osf.io), scientific journals, national governments, international institutions, NGOs, etc. Inspired by the great [Reprohacks](https://reprohack.github.io/reprohack-hq/), content suggestions are enouraged. That is, if you'd like to have a data dashboard created for a certain, open-access data set, let us know, and the participants may want to take it on.

- **Purpose**: Extend the original presentation of the data. This may include the linking to additional data, new visualisations, etc.

- **Output**: The various output (e.g., data dashboards) will be (co-)authored by the participants who develop it. Time constraints notwithstanding, a lot of this output may be very enticing for further development, by the same participants or by anyone else. For this purpose, participants are encouraged to publish their code on **open access**, for instance on Github.

![](https://raw.githubusercontent.com/pablobernabeu/data-is-present/master/dashboard%20gif.gif)
