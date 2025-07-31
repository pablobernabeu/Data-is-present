# *Data is present:* [workshops](#workshops) and [datathons](#datathons-creating-reproducible-documents-and-dashboards)

## Enhanced data presentation using reproducible documents and dashboards

<br>

| Date  | Title        | Event and location   | Registration   |
| :---: | ------------ | -------------------- | :------------: |
| 26 Nov 2020 | [Mixed-effects models in R, and a new tool for data simulation](https://pablobernabeu.github.io/talk/2020-11-26-mixed-effects-models-in-r-and-a-new-tool-for-data-simulation/) | New Tricks Seminars, Dept. Psychology, Lancaster University [online] |  |
| 8 Oct 2020 | [Reproducibilidad en torno a una aplicación web](https://pablobernabeu.github.io/talk/2020-10-08-reproducibilidad-en-torno-a-una-aplicacion-web/) | Reprohack en español, LatinR Conference 2020 [online] | [Link](https://www.eventbrite.com.ar/e/reprohack-en-espanol-latinr-2020-tickets-121741832097) |
| 13 Aug 2020 | [Open data and reproducibility v2.1: R Markdown, data dashboards and Binder](https://github.com/pablobernabeu/CarpentryCon-2020-workshop-Open-Data-Reproducibility) (co-led with Florencia D'Andrea) | [CarpentryCon@Home](https://2020.carpentrycon.org/schedule/), The Carpentries [online] | [Link](https://2020.carpentrycon.org/schedule/) |
| 26 July 2020 | [Open data and reproducibility](https://github.com/pablobernabeu/UKCLC2020-workshop-Open-data-and-reproducibility) (co-led with Eirini Zormpa) | [UK Cognitive Linguistics Conference](https://www.ukclc2020.com/pre-conference), University of Birmingham [online] | [Link](https://www.ukclc2020.com/registration) | 
| 6 May 2020 | [R Markdown workshop](#workshop-2-r-markdown-documents) | Lancaster University [online] | |
| Event cancelled | [Open data and reproducibility v2.0](https://newcastle2020.satrdays.org/) | [SatRday Newcastle upon Tyne](https://newcastle2020.satrdays.org/), Newcastle University | [Link](https://newcastle2020.satrdays.org/) |

<br>

### Background

This project offered free activities to learn and practise reproducible data presentation. [Pablo Bernabeu](https://www.software.ac.uk/about/fellows/pablo-bernabeu) organised these events in the context of a [Software Sustainability Institute Fellowship](https://www.software.ac.uk/programmes-and-events/fellowship-programme).

#### Open-source software

Programming languages such as [R](https://www.r-project.org/about.html) and [Python](https://www.python.org/) offer free, powerful resources for data processing, visualisation and analysis. Experience in these programs is highly valued in data-intensive disciplines.

#### Open data

Original data has become a [public good in many research fields](https://www.nature.com/articles/d41586-019-01506-x) thanks to cultural and technological advances. On the internet, we can find innumerable data sets from sources such as scientific journals and repositories (e.g., [OSF](https://osf.io)), local and national governments (e.g., [London](https://data.london.gov.uk/), UK [[1](https://www.ukdataservice.ac.uk/), [2](https://data.gov.uk/)]), non-governmental organisations (e.g., [data.world](https://data.world/datasets/ngo)), etc. Researchers inside and outside academia nowadays share a lot of their data under attribution licences (e.g., [Creative Commons](https://creativecommons.org/), the UK [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/1/), etc.). This allows any external analysts to access these raw data, create (additional) visualisations and analyses, and share these. In society, making data more accessible can [demonstrably benefit citizens](https://digitalcommons.law.yale.edu/cgi/viewcontent.cgi?article=1140&context=yhrdlj) (despite [limitations](https://firstmonday.org/ojs/index.php/fm/article/view/3316/2764#author)).

## Activities

Activities comprise free **workshops** and [**datathons**](#datathons-creating-reproducible-documents-and-dashboards).

### Workshops

[R is a programming language](https://www.r-project.org) greatly equipped for the creation of reproducible documents and dashboards. Four workshops are offered that cover a suite of interrelated tools—R, R Markdown, data dashboards and Binder environments—, all underlain by reproducible workflows and open-source software.

Each workshop includes **taught and practical sections**. The practice provides a chance for participants to experience and address common issues with the code. The level of taught sections is largely tailored to participants; similarly, practice sections are individually adaptable by means of easier and tougher tasks. The duration is also flexible, and some of the workshops can be combined into the same session.

The [RStudio](https://rstudio.com/) interface is used in all workshops. Multi-levelled, real code examples are used. Throughout the workshops, and especially in the practice sections, individual questions will be encouraged.

#### Workshop 1: Introduction to R

This workshop can serve as an introduction to R or a revision. It demonstrates what can be done in R, and provides resources for individual training. Since the duration is limited, online courses are also recommended ([see examples](https://www.coursera.org/courses?query=r) and [fee waivers for full content](https://learner.coursera.help/hc/en-us/articles/209819033-Apply-for-Financial-Aid-or-a-Scholarship)).

- [Data structures](http://adv-r.had.co.nz/Data-structures.html)
- [Packages](http://www.sthda.com/english/wiki/installing-and-using-r-packages): general-purpose examples (e.g., [tidyverse](https://www.tidyverse.org/)) and more specific ones (e.g., for [statistics](https://cran.r-project.org/web/packages/lsr/lsr.pdf) or [geography](https://cran.r-project.org/web/packages/GEOmap/GEOmap.pdf))
- [Loading and writing data, in native and foreign formats](https://cran.r-project.org/web/packages/rio/vignettes/rio.html)
- *Tidy* format
- *Wide* versus *long* format. For most processes in R, [data needs to be in a tidy, long format](https://r4ds.had.co.nz/tidy-data.html).

<p align = 'center'> <a href = 'https://doi.org/10.1371/journal.pbio.3000202.g001'> <img width = '28%' src = 'https://journals.plos.org/plosbiology/article/file?id=10.1371/journal.pbio.3000202.g001&type=large' alt = 'Illustration of wide and tidy data formats, from Postma and Goedhart (2019)' /> </a> <p align = 'center' style = 'text-align:center;'> Illustration from [Postma and Goedhart (2019)](https://doi.org/10.1371/journal.pbio.3000202.g001). </p> </p>

- [Combining data sets](https://psyteachr.github.io/msc-data-skills/joins.html#joins)
- [Data summaries](http://www.cookbook-r.com/Manipulating_data/Summarizing_data/)
- [Plots with `ggplot2::ggplot()`](https://philmcaleer.github.io/ug2-practical/visualisation-through-ggplot2.html)
- [Interactive plots with `plotly::ggplotly()`](https://plot.ly/ggplot2/)
- [Statistics](https://learningstatisticswithr-bookdown.netlify.com/part-v-statistical-tools.html)
  - [Linear mixed-effects models](https://psych.wisc.edu/Brauer/BrauerLab/wp-content/uploads/2014/04/Brauer_and_Curtin_LMEMs-2017-Psych_Methods.pdf) (see also [a review of practices](https://www.sciencedirect.com/science/article/pii/S0749596X20300061?dgcid=coauthor#b0670))
- [How functions work](https://swcarpentry.github.io/r-novice-inflammation/02-func-R/)
- *Debugging*. Code errors are known as bugs. They can tiresome, but also interesting sometimes! :sweat_smile: Some tips for the first many years of experience include: reading and investigating error messages, in both source and console windows; controlling letter case and typos; closing parentheses and inverted commas; ensuring to have the necessary packages installed and loaded; following the format required by each function. To debug, break up code into subcomponents and test each of those to find out the source of the error. Once we act on that, the best outcome is seeing the code work, but sometimes different errors overlap, in which case we may see one error disappearing before another one appears. Debugging soon leads to proficient information seeking. The search process often begins on an internet search engine and extends to user communities, package documentation, tutorials, blogs... (see [video explanation](https://youtu.be/Nj9J5iCSMB0?t=2687)). [Advanced debugging tools are also available](https://adv-r.hadley.nz/debugging.html).
- Vast availability of free resources on the internet, from [Coursera](https://www.coursera.org/courses?query=r%20programming) and other MOOC sites, [RStudio](https://education.rstudio.com/), [University of Glasgow](https://psyteachr.github.io/), [Carpentries](http://swcarpentry.github.io/r-novice-inflammation/), etc.
- Community: [StackOverflow](https://stackoverflow.com/), [RStudio Community](https://community.rstudio.com/), [Github issues](https://github.com) (e.g., for R packages), etc. Using and contributing back.
- [RStudio Cloud](https://rstudio.cloud/): a personal RStudio environment on the internet

#### Workshop 2: R Markdown documents

Set your input and output in stone using [R Markdown](https://rmarkdown.rstudio.com/). The analysis reports may be enriched with website features (HTML/CSS) and published as HTML, PDF or Word documents. Moreover, with R packages such as `bookdown`, `bookdownplus`, `blogdown` and `flexdashboard`, documents can be formatted as [websites](https://awesome-blogdown.com/), [digital papers and books](https://bookdown.org/) and [data dashboards](https://rmarkdown.rstudio.com/flexdashboard/). Other useful packages include `rmarkdown`, `knitr`, `DT`, `kableExtra` and `ggplot2`. Further background: [presentation by Michael Frank](https://www.youtube.com/watch?v=Nj9J5iCSMB0), [slides by Ed Berry](https://www.eddjberry.com/talks/reproducible-writing-with-rmarkdown.html#1).

As well as facilitating the reproducibility of analyses and results to third parties, R Markdown is helpful *during the creation* of a report. In particular, it reduces the chances of errors and the number of repetitive tasks. For instance, any part of the data can be inputted in the text directly from the source, rather than manually copying it (e.g., `` `r "\u0060r mean(dat[dat$location=='Havana', 'measure'])\u0060"` `` ([expand](https://bookdown.org/yihui/rmarkdown/r-code.html)). Thus, if and when the analysis needs to be changed or updated, the report can be automatically updated at the click of a button. In another area, the captions for figures and tables can be automatised using [cross-reference labels](https://bookdown.org/yihui/rmarkdown-cookbook/cross-ref.html) (e.g., Table `\@ref(tab:mtcars)`). This secures the match between the text and the captions of figures and tables, and it automatically updates the numbering whenever and wherever a new figure or table is introduced.

<p align = 'center'> <a href = 'https://bookdownplus.netlify.com/portfolio/'> <img width = '50%' src = 'https://github.com/pablobernabeu/bookdownplus/blob/master/inst2/copernicus/showcase/copernicus2.png?raw=true' alt = 'Example of paper created with bookdownplus (image retrieved from R bookdownplus package)'/> </a> <p align = 'center' style = 'text-align:center;'> Image from bookdownplus package (https://bookdownplus.netlify.com/portfolio/).</p></p>

#### Workshop 3: Introduction to web applications and dashboards

[Data dashboards are web applications used to visualise data](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.01782/full) in detail through tables and plots. They assist in explaining and accounting for our data processing and analysis. They don't require any coding from the end user. While most dashboards and web applications present existing data, a few of them serve the purpose of creating or simulating new data (see [example](https://github.com/pablobernabeu/Experimental-data-simulation)).

<p align = 'center'> <a href = 'https://pablobernabeu.github.io/2017/the-case-for-data-dashboards-first-steps-in-r-shiny/'> <img width = '80%' src = 'https://pablobernabeu.github.io/2017/the-case-for-data-dashboards-first-steps-in-r-shiny/8.png' alt = 'Illustration of the usage of dashboards alongside data repositories' /> </a> </p>

These all-reproducible dashboards are published as websites, and thus, they can include hyperlinks and downloadable files. Some of the R packages used are `knitr`, `DT`, `kableExtra`, `reactable`, `ggplot2`, `plotly`, `rmarkdown`, `flexdashboard` and `shiny`. The aim of this workshop is to practise creating different forms of dashboards—[Flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) and [Shiny](https://shiny.rstudio.com/)—the latter of which offers [greater features](https://mastering-shiny.org/), and to practise also with the hosting platforms fitting each type—such as personal websites, [RPubs](https://rpubs.com/), [Binder](https://mybinder.org/), [Shinyapps](https://www.shinyapps.io/) and [custom servers](https://rstudio.com/products/shiny/shiny-server/). A great thing about dashboards is that they may be made very simple, but they can also be taken to the next level using some HTML, CSS or Javascript code (on top of the back-end code present in the R packages used), which is addressed in the next workshop.

#### Workshop 4: Binder environments and improving data dashboards

##### Binder

[Binder](https://mybinder.org/) is a tool to facilitate public access to software environments—for instance, by publishing an RStudio environment on the internet. Binder can also host Shiny apps. It is generously free [for users](https://discourse.jupyter.org/t/mybinder-org-cost-updates/2426). After looking at the [nuts and bolts of a deployment](https://github.com/binder-examples/r), participants will be able to deploy their own Binder environments and check the result by the end of the workshop. For this purpose, it's recommended to have data and R code ready, ideally in a GitHub repository.

##### Improving data dashboards

We will practise how to improve the functionality of dashboards using some HTML, CSS and Javascript code, which is [the basis of websites](https://www.w3schools.com/whatis/).

```
<!-- Javascript function to enable a hovering tooltip -->
<script>
$(document).ready(function(){
    $('[data-toggle="tooltip1"]').tooltip();
});
</script>
```

<p align = 'center'> <a href = 'https://shiny.rstudio.com/gallery/'> <img align = 'center' width = '60%' src = 'https://raw.githubusercontent.com/pablobernabeu/data-is-present/master/dashboard%20gif.gif' alt = 'Examples of data dashboards' /> </a> </p>

##### Trade-offs among dashboards

Next, we will practise with three dashboard types—[Flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/using.html), [Shiny](https://shiny.rstudio.com/tutorial/) and [Flexdashboard-Shiny](https://rmarkdown.rstudio.com/flexdashboard/shiny.html)—and with the suitable hosting platforms. Firstly, the strength of Flexdashboard ([example](http://rpubs.com/pcbernabeu/Dutch-modality-exclusivity-norms)) is its basis on R Markdown, yielding an unmatched user interface (*front-end*). Secondly, the strength of Shiny ([example](https://mybinder.org/v2/gh/pablobernabeu/Modality-switch-effects-emerge-early-and-increase-throughout-conceptual-processing/master?urlpath=shiny/Shiny-app/)) is the input reactivity (*back-end*) it offers, allowing users to download sections of data they select, in various formats. Last, Flexdashboard-Shiny ([example](https://pablobernabeu.shinyapps.io/dutch-modality-exclusivity-norms/)) combines the best of both worlds.

<p align='center'>
    &#x2605; <b> Flexdashboard </b> &#x2605;
</p>

<p align='center'>
    &#x2605; &#x2605; <b> Shiny </b> &#x2605; &#x2605;
</p>

<p align='center'>
    &#x2605; &#x2605; &#x2605; <b> Flexdashboard-Shiny </b> &#x2605; &#x2605; &#x2605;
</p>

Flexdashboard types are rendered as an HTML document—simple websites—, and can therefore be easily published on personal sites or [RPubs](https://rpubs.com/). This is convenient because no special hosting is required. In contrast, Shiny and Flexdashboard-Shiny types offer greater features, but require Shiny servers. Fortunately, the shinyapps.io server is available for free, up to some [usage limit](https://www.shinyapps.io/). This server can host any of the three dashboards mentioned here. Another good option is presented by Binder environments, which can host the Shiny-type dashboards with no (explicit) limit. Yet, the Flexdashboard-Shiny type cannot be hosted in this server ([as of January 2020, at least](https://github.com/jupyter/repo2docker/issues/799)). Consequently, greater functionality may come at a cost for dashboards that have any considerable traffic, whereas dashboards with low traffic may do well on shinyapps.io. Knowing these trade-offs can help navigate [usage limits](https://support.rstudio.com/hc/en-us/articles/217592947-What-are-the-limits-of-the-shinyapps-io-Free-plan-), save on web hosting fees, and increase the availability of our dashboards online, as we can offer fall-back versions on different platforms, as in the example below:

> ... *[preferred-dashboard](https://pablobernabeu.shinyapps.io/dutch-modality-exclusivity-norms/) (in case of downtime, please visit this [alternative](http://rpubs.com/pcbernabeu/Dutch-modality-exclusivity-norms))*

Transforming dashboards into the different versions can be as easy as enabling or disabling some features, especially input reactivity. For instance, if we want to downgrade a Flexdashboard-Shiny to a Flexdashboard, to publish it outside of a Shiny server (see [example](https://github.com/pablobernabeu/Modality-exclusivity-norms-Bernabeu-et-al/blob/master/Dutch-modality-exclusivity-norms-RPubs.Rmd)), we must delete `runtime:shiny` from the header, and disablen Shiny reactive inputs and objects, as below.

````
```{r}
# Number of words selected on sidebar
# reactive(cat(paste0('Words selected below: ', nrow(selected_props()))))
```
````

##### Free accounts and tips

Hosting sites have specific terms of use. For instance, [shinyapps.io](https://www.shinyapps.io/) has a free starter license with limited use. Free apps can handle a large but limited amount of data, and up to five apps may be created. Beyond this, RStudio offers a wide range of subscriptions starting at $9/month.

Memory and traffic limits of the free shinyapps.io account can sometimes present problems when heavy data data sets are used, or there are many visits to the app. The memory overload issue is often flagged as `Shiny cannot use on-disk bookmarking`, whereas excessive traffic may see the app not loading. Fortunately, usage limits need not always require a paid subscription or a [custom server](https://www.r-bloggers.com/alternative-approaches-to-scaling-shiny-with-rstudio-shiny-server-shinyproxy-or-custom-architecture/), thanks to the following workarounds:

- develop app locally as far as possible, and only deploy to shinyapps.io only at the last stage;
- prune data set, leaving only the necessary data;
- if necessary, unlink data by splitting it into different sets, reducing computational demands;
- if necessary, use various apps (five are allowed in each free shinyapps.io account);
- if necessary, link from the app to a PDF with visualisations requiring heavy, interlinked data. High-resolution plots can be rendered into a PDF document in a snap, using code such as below.

        
      pdf('List of plots per page', width = 13, height = 5)
      print(plot1)
      print(plot2)
      # ...
      print(plot150)﻿
      dev.off()
        

Conveniently, all text in a PDF—even in plots—is indexed, so it can be searched [ Ctrl+f / Cmd+f / 🔍 ] (see [example](https://osf.io/2tpxn/)). Furthermore, you may also [merge the rendered PDF with any other documents](http://www.ilovepdf.com/).

#### Prerequisites and suggestions for participation in each workshop

*Necessary:* laptop or computer with [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/download/) installed, or access to [RStudio Cloud](https://rstudio.cloud/); familiarity with the content of the preceding workshops through the web links herein.

*Suggested:* having your own data and R code ready (on a Github repository if participating in Workshop 4); participation in some of the preceding workshops.


### Datathons: creating reproducible documents and dashboards

In these coding meetups, participants collaborate to create reproducible documents or dashboards using the data and software they prefer (see [examples](https://github.com/pablobernabeu/Data-is-present/tree/master/examples-documents-dashboards)). Since the work can be split across different people and sections, some nice products may be achieved within a session. Any programming languages may be used.

- **Data used:** academic or non-academic data of your own or from open-access sources such as [OSF](https://osf.io), scientific journals, governments, international institutions, NGOs, etc.

  - Inspired by the great [Reprohacks](https://reprohack.github.io/reprohack-hq/), content suggestions are encouraged. That is, if you'd like to have a reproducible document or dashboard created for a certain, open-access data set, please let us know, and some participants may take it on. Suggestions may be posted as [issues](https://github.com/pablobernabeu/Data-is-present/issues) or emailed to p.bernabeu@lancaster.ac.uk.

- **Purposes**

  - collaborating to visualise data in novel ways using reproducible documents or interactive dashboards. For this purpose, participants sometimes draw on additional data to look at a bigger picture;

  - reflecting on the process by reviewing the techniques applied and challenges encountered.

- **Output:** A key aspect of datathons is the creation of output. Documents and dashboards are (co-)authored by the participants who work on them, who can then publish them on their websites, or on [RPubs](https://rpubs.com/), [Binder](https://mybinder.org/), [Shinyapps](https://www.shinyapps.io/) or [custom servers](https://rstudio.com/products/shiny/shiny-server/). Time constraints notwithstanding, a lot of this output may be very enticing for further development by the same participants, or even by other people if the code is shared online. Just like with data, an attribution licence can be attached to the code.

#### Prerequisites and suggestions for participation in datathons

*Necessary:* basic knowledge of reproducible documents or dashboards. 

*Suggested:* familiarity with the development of reproducible documents or dashboards; an idea about the data you'd like to work with and the kind of document or dashboard you want to create.

## Contact 

Please submit any queries or requests by [posting an issue](https://github.com/pablobernabeu/Data-is-present/issues) or emailing p.bernabeu@lancaster.ac.uk.

-------------

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />Work licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. Linked-to content is independent.
