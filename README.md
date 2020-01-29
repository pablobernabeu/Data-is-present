# *Data is present:* open workshops and hackathons

### Enhanced presentation of open data using reproducible reports and dashboards

Original data is increasingly accessible thanks to cultural and technological advances. On the internet, we can find innumerable data sets from sources such as scientific journals and repositories (e.g., [OSF](https://osf.io)), local and national governments (e.g., [London](https://data.london.gov.uk/), UK [[1](https://www.ukdataservice.ac.uk/), [2](https://data.gov.uk/)]), and non-governmental organisations (e.g., [data.world](https://data.world/datasets/ngo)). Often, these data may be presented in novel ways, by creating new tables or plots, or by integrating additional data. Free, open-source software has become a great companion for open data.

This open scholarship project offers free workshops and coding meet-ups (hackathons) to learn and practise data presentation, across the UK. It was made possible by a [fellowship of the Software Sustainability Institute](https://www.software.ac.uk/programmes-and-events/fellowship-programme) awarded to [Pablo Bernabeu](https://www.software.ac.uk/about/fellows/pablo-bernabeu).

## Open access data

Research data is increasingly treated as a [public good](https://www.nature.com/articles/d41586-019-01506-x). Academics and non-academic researchers (scientists, governments, NGOs) nowadays share a lot of their data under citation-based licences (e.g., [Creative Commons](https://creativecommons.org/), the UK [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/1/), etc.). This allows any analysts to access these raw data, perform the visualisations and analyses they like, and share these.

## Open source software

Programs such as [R](https://www.r-project.org/about.html) and [Python](https://www.python.org/) offer free, powerful resources for data processing, visualisation, and analysis. Experience in these programs is highly valued in data-intensive sectors of the job market.

## Activities

With reproducible reports and dashboards in the centre, this project includes training and practice sessions throughout 2020 and into the first quarter of 2021. The training will be useful on its own, and will also pave the way to joining the practice sessions. All activities are available across the UK.

### R workshops

Four participatory, practical workshops in [R](https://www.r-project.org) are on offer, specifically using [RStudio](https://rstudio.com/). The reason for choosing R is that it has great packages for creating reproducible reports and dashboards.

These workshops cover a suite of interrelated tools based on R and Docker. The three tools—R Markdown, data dashboards, and Binder environments—are all underlain by freeware, inexpensive applications, and reproducible workflows. The usefulness of these tools extends from academia to data science. 

In each session, common challenges will be flagged based on multi-levelled, real examples, and resources for further practice will be provided. Every workshop will have a taught part and a hands-on part. The level of the taught content will be largely tailored to the audience, and the hands-on part will be individually adaptable thanks to easier and tougher tasks available. To fully cater to the possibilities of different audiences, different workshops can be combined into the one session, and the duration can also be tailored.

*Prerequisites:* R (https://www.r-project.org/) and RStudio (https://rstudio.com/products/rstudio/download/). 

*Recommended preparation:* Familiarity with the content linked on this page; possibly also having your own data and R code (on a Github repository for Workshop 4).

1. **Introduction to R:**

- Object-oriented programming;
- Data structures;
- Loading and writing data, in native and foreign formats;
- Packages: field-specific examples and [tidyverse](https://www.tidyverse.org/);
- Functions;
- Debugging;
- Vast availability of free resources on the internet (e.g., from [RStudio](), [Glasgow University](), and [many more](https://twitter.com/nickgaspelin/status/1219699050741714944));
- Community ([RStudio Community](https://community.rstudio.com/), [StackOverflow](https://stackoverflow.com/), etc.): using and contributing;
- [RStudio Cloud](https://rstudio.cloud/), a great, individual RStudio environment online.

2. **[R Markdown reports](https://rmarkdown.rstudio.com/)** —  Set your input and output beautifully in stone. These reports may be enriched with website features (HTML/CSS), and published as websites, PDF, or Word. Moreover, by using R packages such as `pagedown`, `blogdown`, `bookdown`, `flexdashboard`, reports can be turned into blogs, books, and data dashboards. 

3. **Introduction to data dashboards** —  [Web applications can be used to visualise data](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.01782/full) in detail through tables and plots. These all-reproducible dashboards are published as websites, and thus, they can include hyperlinks and downloadable files. Users need not program. Some of the R packages used are `knitr`, `reactable`, `ggplot`, `plotly`, `rmarkdown`, `flexdashboard`, and `shiny`. The aim is to look at different forms of dashboards ([Flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) and [Shiny](https://shiny.rstudio.com/)), and the suitable platforms for online hosting (personal websites and RPubs, Binder, Shinyapps, and custom servers). A great thing: dashboards may be made very simple, but they also offer the possibility of infinite improvement by drawing on HTML, CSS, and Javascript.

<p align = 'center'> <img align = 'middle' width = '70%' src = 'https://media-exp1.licdn.com/dms/image/C4D12AQHYcdpmcmSypg/article-inline_image-shrink_1500_2232/0?e=1585785600&v=beta&t=0xfTYFRu_OsWN4lkwnO1IonW6HgAuJD79443sf1-4Ms' /> </p>

4. **Intermediate data dashboards and Binder environments** —  More advanced practice with each of the hosting possibilities (e.g., [Flexdashboard website](http://rpubs.com/pcbernabeu/Dutch-modality-exclusivity-norms), [Flexdashboard Shiny](https://pablobernabeu.shinyapps.io/Dutch-modality-exclusivity-norms/#section-table), [Shiny](https://pablobernabeu.shinyapps.io/ERP-waveform-visualization_CMS-experiment/)). Furthermore, we will learn how to use [Binder environments](https://mybinder.org/) to enhance public access to our code (e.g., by publishing an RStudio session on the internet), and to host a dashboard on the internet. This is generously free [for the users](https://discourse.jupyter.org/t/mybinder-org-cost-updates/2426). We'll look at the [nuts and bolts of a Binder deployment](https://github.com/binder-examples/r). Attendees may deploy their own Binder environments.

<p align = 'center'> <img align = 'center' width = '80%' src = 'https://raw.githubusercontent.com/pablobernabeu/data-is-present/master/dashboard%20gif.gif' /> </p>


### Hackathons

These hackathons are half day meetings meetings in which participants will collaborate to create reproducible reports (e.g., R Markdown) or data dashboards (e.g., R Shiny) from any open access data they choose.

*Prerequisites:* Basic knowledge of dashboard development.

*Recommended preparation:* Familiarity with the relevant links herein; an idea about the data and analyses to be performed.

- **Data**: Academic or non-academic, open-access data from sources such as [OSF](https://osf.io), scientific journals, governments, international institutions, NGOs, etc. Inspired by the great [Reprohacks](https://reprohack.github.io/reprohack-hq/), content suggestions are encouraged. That is, if you'd like to have a dashboard created for a certain, open-access data set, let us know, and the participants may want to take it on.

- **Purpose**: Extending the original presentation of the data—if any—by creating tables and plots, integrating additional data, etc.

- **Output**: A central goal of these meet-ups is the creation of output—especially reports and dashboards. These will be (co-)authored by the participants who develop them. Time constraints notwithstanding, a lot of this output may be very enticing for further development, by the same participants or other people, if the code is openly shared (highly encouraged). Just like with the data that is used, a citation-based licence can be attached to this code.
