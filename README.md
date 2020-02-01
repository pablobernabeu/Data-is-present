# *Data is present:* open workshops and hackathons

## Enhanced data presentation using reproducible documents and dashboards

This open scholarship project offers free workshops and coding meet-ups to learn and practise data presentation across the UK, throughout 2020 and into the first quarter of 2021. It was made possible by a [fellowship of the Software Sustainability Institute](https://www.software.ac.uk/programmes-and-events/fellowship-programme) awarded to [Pablo Bernabeu](https://www.software.ac.uk/about/fellows/pablo-bernabeu).

### Background

#### Open data

Original data has become a [public good in many research fields](https://www.nature.com/articles/d41586-019-01506-x), thanks to cultural and technological advances. On the internet, we can find innumerable data sets from sources such as scientific journals and repositories (e.g., [OSF](https://osf.io)), local and national governments (e.g., [London](https://data.london.gov.uk/), UK [[1](https://www.ukdataservice.ac.uk/), [2](https://data.gov.uk/)]), non-governmental organisations (e.g., [data.world](https://data.world/datasets/ngo)), etc. Researchers inside and outside academia nowadays share a lot of their data under citation-based licences (e.g., [Creative Commons](https://creativecommons.org/), the UK [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/1/), etc.). This allows any analysts to access these raw data, create (additional) visualisations and analyses, and share these.

#### Open software

Open-source programs such as [R](https://www.r-project.org/about.html) and [Python](https://www.python.org/) offer free, powerful resources for data processing, visualisation and analysis. Experience in these programs is highly valued in data-intensive disciplines.

## Activities

### R workshops

[R is a programming language](https://www.r-project.org) greatly equipped for creating reproducible documents and dashboards. Four, free workshops in R are available which cover a suite of related tools. These tools—R Markdown, data dashboards and Binder environments—are all underlain by freeware and reproducible workflows. Experience with these tools is valued in many fields.

Every workshop has a taught part and a practical part. The level of the taught content is largely tailored to the audience, and the practical part is individually adaptable thanks to the availability of easier and tougher tasks. Throughout the workshops, and especially during the practical part, individual questions will be welcome. To fully cater to different audiences, some workshops can be combined into the one session, and the duration can also be tailored. The [RStudio](https://rstudio.com/) interface will be used in all workshops. Multi-levelled, real code examples are used.

*Prerequisites:* Laptop or computer with [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/download/) installed.

*Recommended preparation:* Familiarity with the content linked on this page; possibly also having your own data and R code (on a Github repository for Workshop 4).

1. **Introduction to R:**

- Object-oriented programming;
- Data structures;
- Loading and writing data, in native and foreign formats;
- Packages: general-purpose (e.g., [tidyverse](https://www.tidyverse.org/)) and field-specific examples;
- *Wide*, *long* and [*tidy*](https://r4ds.had.co.nz/tidy-data.html) data formats;
- Joining datasets;
- Data summaries;
- Plots;
- Statistics;
- How functions work;
- Debugging;
- Vast availability of free resources on the internet (e.g., from [RStudio](), [University of Glasgow](), and [many more](https://twitter.com/nickgaspelin/status/1219699050741714944));
- Community: [Github repositories](https://github.com) (e.g., for R packages), [RStudio Community](https://community.rstudio.com/), [StackOverflow](https://stackoverflow.com/), etc. Using and contributing back;
- [RStudio Cloud](https://rstudio.cloud/), a great, personal RStudio environment online.

2. **[R Markdown documents](https://rmarkdown.rstudio.com/)** —  Set your input and output beautifully in stone. These reports may be enriched with website features (HTML/CSS), and published as websites, PDF, or Word. Moreover, with R packages such as `pagedown`, `blogdown`, `bookdown`, and `flexdashboard`, documents can be neatly formatted into blogs, books, and data dashboards.

<p align = 'center'> <a href = 'https://github.com/rstudio/pagedown'> <img width = '70%' src = 'https://user-images.githubusercontent.com/19177171/51005498-5b46cb80-153f-11e9-9026-4b50a9f3d3f1.png' /> </a> <p align = 'center' style = 'text-align:center;'> Image from pagedown: https://github.com/rstudio/pagedown </p> </p>

3. **Introduction to data dashboards** —  [Web applications can be used to visualise data](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.01782/full) in detail through tables and plots. These all-reproducible dashboards are published as websites, and thus, they can include hyperlinks and downloadable files. Users need not program. Some of the R packages used are `knitr`, `reactable`, `ggplot`, `plotly`, `rmarkdown`, `flexdashboard`, and `shiny`. The aim is to practise with different forms of dashboards—namely, [Flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) and [Shiny](https://shiny.rstudio.com/)—, and with the suitable hosting platforms for each type—including personal websites, RPubs, Binder, Shinyapps, and custom servers. A great thing about dashboards is that they may be made very simple, but they can also be taken to the next level by means of HTML, CSS and Javascript code, which is addressed in the next workshop.

<p align = 'center'> <a href = 'https://www.linkedin.com/pulse/shiny-data-presentation-added-value-pablo-bernabeu/'> <img width = '40%' src = 'https://media-exp1.licdn.com/dms/image/C4D12AQHYcdpmcmSypg/article-inline_image-shrink_1500_2232/0?e=1585785600&v=beta&t=0xfTYFRu_OsWN4lkwnO1IonW6HgAuJD79443sf1-4Ms' /> </a> </p>

4. **Binder environments and intermediate data dashboards** —  This session begins by introducing [Binder environments](https://mybinder.org/), a tool to facilitate public access to our code (e.g., by publishing an RStudio session on the internet). These environments can also host Shiny apps. Binder is generously free [for the users](https://discourse.jupyter.org/t/mybinder-org-cost-updates/2426). After looking at the [nuts and bolts of a Binder deployment](https://github.com/binder-examples/r), participants will be able to deploy their own Binder environments and check the result by the end of the workshop. Next, we will turn to data dashboards, to gain further experience with different formats—namely, [Flexdashboard website](http://rpubs.com/pcbernabeu/Dutch-modality-exclusivity-norms), [Flexdashboard-Shiny app](https://pablobernabeu.shinyapps.io/Dutch-modality-exclusivity-norms/#section-table), and [Shiny app](https://pablobernabeu.shinyapps.io/ERP-waveform-visualization_CMS-experiment/)—, and with the suitable hosting platforms. This knowledge helps to save in web hosting fees, and to increase the availability of our dashboards online by enabling fall-back versions on different platforms. Last but not least, we will practise how to improve the functionality of dashboards using some HTML, CSS and Javascript code, which is [the basis of websites](https://www.w3schools.com/whatis/).

<p align = 'center'> <a href = 'https://shiny.rstudio.com/gallery/'> <img align = 'center' width = '60%' src = 'https://raw.githubusercontent.com/pablobernabeu/data-is-present/master/dashboard%20gif.gif' /> </a> </p>


### Hackathons: creating reproducible documents and dashboards

These hackathons are coding meet-ups in which participants collaborate to create reproducible documents (e.g., [R Markdown](https://rmarkdown.rstudio.com/)) or data dashboards (e.g., [R Shiny](https://shiny.rstudio.com/)) from any open-access data they choose.

*Prerequisites:* Basic knowledge of dashboard development, and laptop or computer with [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/download/) installed.

*Recommended preparation:* Familiarity with the relevant links herein; possibly also, having an idea about data and you'd like to work with and the kind of document or dashboard you want to create.

- **Data**: Academic or non-academic, open-access data from sources such as [OSF](https://osf.io), scientific journals, governments, international institutions, NGOs, etc. Inspired by the great [Reprohacks](https://reprohack.github.io/reprohack-hq/), content suggestions are encouraged. That is, if you'd like to have a reproducible document or dashboard created for a certain, open-access data set, please let us know, and some hackathon participants may take it on.

- **Purpose**: Visualising the data in new ways using reproducible documents or interactive dashboards. Sometimes, analysts may also draw on additional data to look at a bigger picture.

- **Output**: A key aspect of these meet-ups is the creation of output. Documents and dashboards are (co-)authored by the participants who develop them, who can then publish them on their own websites, [RPubs](https://rpubs.com/), [shinyapps.io](https://www.shinyapps.io/), etc. Time constraints notwithstanding, a lot of this output may be very enticing for further development, by the same participants or by other people if the code is shared online. Just like with data, a citation-based licence can be attached to the code.
