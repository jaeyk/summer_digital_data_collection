# Research Workshop on Computational Tools for Digital Data Collection

You should ask questions about class material and assignments through the Slack channels so that everyone can benefit from the discussion (not personally emailing to me). We encourage you to respond to each other’s questions as well. A TA will send you an invite to the workspace.

## Description

The focus of this workshop is on digital data collection using R. The workshop consists of four parts. The first session introduces computational social science and the workflow of digital data collection within the frame of tidyverse. The following three sessions will introduce advanced techniques in social media scraping, pdf scraping, and web-scraping. 

The objective of this workshop is practical: participants will develop and execute data collections strategies in each of the three thematic modules, with the final deliverable being three complete and clean datasets. Ideally, I will expect participants involved in the workshop to identify resources---e.g., administrative databases, archival documents, social media accounts---that they wish to scrape.

## Logistics

### Time and Location

Date: 5/19, 5/20, 5/26, 5/27 11 AM - 1 PM (KST)

Location: Zoom (Institute of Politics, Korea University)

### Instructor

<img src="https://jaeyk.github.io/profile.jpg" style="margin-right:4px;" align="left" width="120">

Instructor: Dr. Jae Yeon Kim, Assistant Professor, KDI School of Public Policy and Management

* E-mail: jaeyeonkim@kdis.ac.kr

All course materials will be posted on Github at [https://github.com/jaeyk/digital_data_collection_workshop](https://github.com/jaeyk/summer_digital_data_collection), including class notes, code demonstrations, and **some** sample data.

### Accessibility

This class is committed to creating an environment in which everyone can participate, regardless of background, discipline, or disability. If you have a particular concern, please come to me as soon as possible so that we can make special arrangements.

### Books and Other Resources

There are no official textbooks for this class. Please see [the references](https://github.com/jaeyk/digital_data_collection_workshop/blob/master/B_references.md) (will be updated throughout the semester) for additional references and [the style guides](https://github.com/jaeyk/PS239T/blob/master/style_guides.md) for efficient programming and project management.

### Computer Requirements

The software needed for the course is as follows:

* Access to the UNIX command line (e.g., a Mac laptop, a Bash wrapper on Windows)
* Git
* R and RStudio (latest versions)
* Anaconda and Python 3 (latest versions)

This requires a computer that can handle all this software. Almost any Mac will do the job. Most Windows machines are fine too if they have enough space and memory.

You must have all the software downloaded and installed PRIOR to the first day of class.

See [this guideline](https://github.com/jaeyk/PS239T/blob/master/B_Install.md) for more information on installation.

## Course schedule 

- To view the course contents interactively, please [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jaeyk/summer_digital_data_collection/main?urlpath=rstudio) 

### May 19, 2022: Why digital trace data? & Automating data collection workflow

- Description: introduction to the tidyverse; discussion of efficient and reproducible ways to collect and wrangle data
- R Packages: [dplyr](https://dplyr.tidyverse.org/), [purrr](https://purrr.tidyverse.org/)
- Kim and Ng, [Teaching Computational Social Science for All](https://www.cambridge.org/core/journals/ps-political-science-and-politics/article/teaching-computational-social-science-for-all/66EAB886BCF21C647E2387051D6A9BEF)  

### May 20, 2022: Social media parsing 

- Command-line tool: [twarc](https://github.com/DocNow/twarc)
    - [Installation guideline](https://scholarslab.github.io/learn-twarc/05-install-twarc.html) 
- R packages: 
    - Academic Twitter API: [academictwitteR](https://cran.r-project.org/web/packages/academictwitteR/index.html)
    - RESTful API: [tweetscores](https://github.com/pablobarbera/twitter_ideology/tree/master/pkg/tweetscores), [twitteR](https://cran.r-project.org/web/packages/twitteR/twitteR.pdf), [rtweet](https://github.com/ropensci/rtweet)
    - Streaming API: [streamR](https://github.com/pablobarbera/streamR)
    - Parsing: [tidyjson](https://cran.r-project.org/web/packages/tidyjson/vignettes/introduction-to-tidyjson.html), [tidytweetjson](https://github.com/jaeyk/tidytweetjson)
- References:
    - [Pablo Barbara](https://github.com/pablobarbera), [LSE Social Media Workshop](http://pablobarbera.com/social-media-workshop/social-media-slides.pdf)
    - Steinert-Threlkeld, [2020 APSA Short Course Generating Event Data From Social Media](https://github.com/ZacharyST/APSA2020_EventDataFromSocialMedia)
    - Kim, [Large-scale Twitter Analysis on COVID-19 and Anti-Asian Climate](https://t.co/4Axd0gEQns) ([GitHub](https://github.com/jaeyk/covid19antiasian))
    
### May 21, 2022: PDF parsing 

- Description: introduction to techniques of pdf-scraping; where to look for documents; how to know what to pre-process by hand; identifying recurring patterns in text to exploit for data wrangling; parallel processing
- R Packages: tesseract, magick, zoo, parallel, pdftools
- References:
    - Mock, [Bear and pdftools](https://themockup.blog/posts/2020-04-03-beer-and-pdftools-a-vignette/)
    - Vaughan, [Tidying Excel cash flow spreadsheets using R](https://blog.davisvaughan.com/2018/02/16/tidying-excel-cash-flow-spreadsheets-in-r/)

### May 22, 2022: Web scraping 

- Description: introduction to techniques of web-scraping; identifying and exploiting underlying database structures; knowing when to quit
- R Packages: rvest, jsonlite, zoo, xml, [ralger](https://github.com/feddelegrand7/ralger)
- Chrome plugin: SelectorGadget
- References:
    - Terman, 3I: Web Scraping and Data Management in R ([GitHub](https://github.com/rochelleterman/ESS-webscraping))
    - Vaughan, [Which RStudio blog posts “pleased” Hadley? A tidytext + web scraping analysis](https://blog.davisvaughan.com/2017/08/16/hadley-pleased/)

## Special thanks 

This course is a remix version of the workshop that I co-taught with Nick Kuipers (Berkeley PhD; currently a postdoc at Stanford) at Berkeley in 2020. I also thank Justin Ho (Academia Sinica) for sharing his teaching materials on the Twitter academic API co-authored with Christopher Barrie (Edinburgh).
