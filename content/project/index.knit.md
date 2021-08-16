---
title: "STA 199 Final Project"
---

*More detail about the project will be released when the project is assigned.*

<!--
## Timeline

Proposal due **Friday, October 9**

Draft report due **Wednesday, October 28** 

Peer feedback due **Thursday, November 5**

Final written report due **Sunday, November 15** 

Presentation video, slides, repo due **Tuesday, November 17**

Presentation comments due **Friday, November 20**

## Introduction 

**TL;DR**: *Pick a dataset and do something with it. That is your 
final project.*

The final project for this class will consist of analysis on a dataset of your own choosing. The dataset may already exist, you may collect your own data by scraping the web.  

Choose the data based on your group's interests or work you all have done in other courses or research projects. The goal of this project is for you to demonstrate proficiency in the techniques we have covered in this class (and beyond, if you like!) and apply them to a dataset to analyze it in a meaningful way. 

### Logistics

You will work on the project with your lab groups.

The four primary deliverables for the final project are

- A written, reproducible report detailing your analysis
- A GitHub repository corresponding to your report
- Slides + a video presentation
- Formal peer review on another team's project

## Overall grading

The grade breakdown is as follows:

Total                                                   | 115 pts
--------------------------------------------------------|--------
**Project proposal**                                    | 10 pts
**Written report**                                      | 50 pts
**Slides**                                              | 15 pts
**Repository**                                          | 5 pts
**Video presentation**                                  | 20 pts
**Peer feedback**                                       | 15 pts

**<i>Note: No late projects are accepted.</i>**

## Data sources

In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple relationships can be explored. Therefore, **your dataset must have at least 50 observations and at least 10 variables (exceptions can be made but you must speak with me first).**

In the dataset, there should be 

- categorical variables
- discrete numerical variables 
- continuous numerical variables 


If you are using a dataset that comes in a 
format that we haven't encountered in class (for instance, a `.DAT` file), make 
sure that you are able to load it into RStudio as this can be tricky depending 
on the source. If you are having trouble, ask for help before it is too late.

**Reusing datasets from class:** Do not reuse datasets used in examples / homework 
in the class. 

Some resources that may be helpful:

- [R Data Sources for Regression Analysis](https://rfun.library.duke.edu/blog/data-sources-for-regression-analysis/)
- [kaggle](https://www.kaggle.com/datasets)
- [FiveThirtyEight data](https://data.fivethirtyeight.com/)
- [TidyTuesday](https://github.com/rfordatascience/tidytuesday)


Additions:

- [World Health Organization](https://www.who.int/gho/database/en/)
- [The National Bureau of Economic Research](https://data.nber.org/data/)
- [International Monetary Fund](https://data.imf.org/?sk=388DFA60-1D26-4ADE-B505-A05A558D9A42&sId=1479329328660)
- [General Social Survey](http://gss.norc.org/)
- [United Nations Data](http://data.un.org/)
- [United Nations Statistics Division](https://unstats.un.org/home/)
- [U.K. Data](https://data.gov.uk/)
- [U.S. Data](https://www.data.gov/)
- [U.S. Census Data](https://www.census.gov/data.html)
- [European Statistics](https://ec.europa.eu/eurostat/)
- [Statistics Canada](https://www.statcan.gc.ca/eng/start)
- [Pew Research](https://www.pewresearch.org/download-datasets/)
- [UNICEF](https://data.unicef.org/)
- [CDC](https://www.cdc.gov/datastatistics/index.html)
- [World Bank](https://datacatalog.worldbank.org/)
- [Election Studies](https://electionstudies.org//)

All analyses must be done in RStudio, and your final written report and 
analysis **must be reproducible**. This means that you must create an R Markdown
document attached to a GitHub repository that will create your written report
exactly upon knitting.

## Project proposal 

There are two main purposes of the project proposal:

- To help you think about the project early, so you can get a head start on finding data, reading relevant literature, thinking about the questions you wish to answer, etc.
- To ensure that the data you wish to analyze, methods you plan to use, and the scope of your analysis are feasible and will help you be successful for this project.

Include the following in the proposal: 

### Section 1 - Introduction

The introduction section includes 

- an introduction to the subject matter you're investigating
- the motivation for your research question (citing any relevant literature)
- the general research question you wish to explore 
- your hypotheses regarding the research question of interest. 

### Section 2 - Data description 

In this section, you will describe the data set you wish to explore. This includes a description of the observations in the data set, a general description of the variables in the data set, and a description of how the data was originally collected (not how you found the data but how the original curator of the data collected it). 

### Section 3 - Glimpse of data

Use the `glimpse` function print a summary of the data at the end of your proposal.

Place your data in the `/data` folder of the repo. Later on you will include the codebook in the README of the data folder. 

### Submission

Submit the PDF of your proposal in the **Project Proposal** assignment on Gradescope. Be sure to select the names of all team members in the submission. The proposal is due on **Friday, October 9.** 

### Proposal grading

Total                                                   | 10 pts
--------------------------------------------------------|--------
**Introduction**                                        | 4 pts
**Data description**                                    | 4 pts
**Glimpse of data**                                     | 2 pts

## Peer feedback

Critically reviewing others' work is a crucial part of the scientific process, and STA 199 is no exception. You will be assigned a team to review. As part of the review process, you must provide your partner team a copy of your current report by **Wednesday, October 28**. After giving the report to your partner team, they will have until **Friday, November 5** to provide a detailed critique about the written report and data analysis. This feedback is intended to help you create a high quality final project, as well as give you experience 
reading and constructively critiquing the work of others.

During the peer feedback process, you will be provided read-only access to your  partner team's GitHub repo. Provide your feedback in the form of GitHub issues to your partner team's GitHub repo. 

Peer feedback will be graded on the extent to which it comprehensively and constructively addresses the components of the partner team's report: the research context and motivation, exploratory data analysis, and any inference, modeling, or conclusions. As you work on the draft, the focus should be on the analysis and less on crafting the final report. **Your draft must include a reasonable attempt at each analysis component - exploratory data analysis, inference or modeling, and drawing initial conclusions.** 

## Written report

Your written report must be done using R Markdown. All team members must contribute to the GitHub repository, with regular meaningful commits. 

Before you finalize your write up, make sure the printing of code chunks is off with the option `echo = FALSE`. 

**Submit the final report on Gradescope under the <i>Written Report</i> assignment on Gradescope.** Your final report must match your GitHub repository *exactly*. The mandatory components of the report are below. You are free to add additional sections as necessary. The report, including visualizations, should be **no more than 10 pages long.** There is no minimum page requirement; however, you must comprehensively address all of the aspects mentioned below.

Please be judicious in what you include in your final write-up.

The written report is worth 50 points, broken down as

Total                                                   | 50 pts
--------------------------------------------------------|--------
**Introduction/data**                                   | 8 pts
**Methodology**                                         | 17 pts
**Results**                                             | 17 pts
**Discussion**                                          | 8 pts


### Introduction and data

The introduction should introduce your general research question and your data  (where it came from, how it was collected, what are the cases, what are the  variables, etc.). 

### Methodology 

The methodology section should include the variables used to address your research question, as well as any useful visualizations or summary statistics. Additionally, you should introduce and justify the statistical method(s) that you believe will be useful in answering your research question. 

### Results 

Showcase how you arrived at answers to 
your question using any techniques we have learned in this class (and some beyond, if you're feeling adventurous). Provide the main results from your analysis. The goal is not to do an exhaustive 
data analysis (i.e., do not calculate every statistic and procedure you have learned for every variable), but rather let me know that you are proficient at asking meaningful questions and answering them with results of data analysis, that you are proficient in using R, and that you are proficient at interpreting 
and presenting the results. Focus on methods that help you begin to answer your research questions. 

### Discussion

This section is a conclusion and discussion. This will require a 
summary of what you have learned about your research question along with statistical arguments supporting your conclusions. Also, critique your own methods and provide suggestions for improving your analysis. Issues pertaining to the reliability and validity of your data and appropriateness of the statistical analysis should also be discussed here. A paragraph on what you would do differently if you were able to start over with the project or what you would do next if you were going to continue work on the project should also be included.


## Presentation Slides

In addition to the write-up, your team must also create presentation
slides that summarize and showcase your project. Introduce your research question and dataset, showcase visualizations, and provide some conclusions. These slides should serve as a brief visual accompaniment to your write-up and will be graded for content and quality. **For submission, convert these slides to a .pdf document to be submitted to Gradescope.** The slides are due on **Tuesday, November 17**.

The slide deck should have no more than **6 content slides + 1 title slide**. Here is a *<u>suggested</u>* outline as you think through the slides; you do *<u>not</u>* have to use this exact format for the slide deck.

- Title Slide
- Slide 1: Introduce the topic and motivation
- Slide 2: Introduce the data
- Slide 3 - 4: Highlights from EDA
- Slide 4 - 5: Inference / modeling
- Slide 6: Conclusions + future work

## Video presentation

Sometime by **Tuesday, November 17**, you/your group will upload a video presentation of your project to Warpwire. Note that all members must present, and that a ten-minute time limit is **strictly enforced**.

For the presentation, you can speak over your slide deck, similar to the lecture content videos. I recommend using Zoom to record your presentation; however, you can use whatever platform works best for your group. Below are a few resources to help you record video presentations:

- [Recording presentations in Zoom](https://kb.siue.edu/61721)
- [Apple Quicktime for screen recording]( https://support.apple.com/en-gb/guide/quicktime-player/qtp97b08e666/mac)
- [Windows 10 built-in screen recording functionality](https://www.youtube.com/watch?v=OfPbr1mRDuo)
- [Kap for screen recording](https://getkap.co/)

You will post the presentation video in Warpwire, which is accessible from the the course Sakai site (bottom of the left-hand tool bar). 

**To upload your video to Warpwire:**

- Click the Warpwire tab in the course Sakai site.
- Click the “+” and select “Upload files”.
- Locate the video on your computer and click to upload.
- Once you’ve uploaded the video to Warpwire, click to share the video and make
a copy of the video’s URL. You will need this when you post the video in the
discussion forum.

**To post the video to the discussion forum:**

- Click the Presentations tab in the course Sakai site. 
- Click the Presentations topic. 
- Click "Start New Presentation". 
- Make the title "Your Team Name: Project Title". For example, "Teaching Team: Analysis of Cars in the US".
- Click the Warpwire icon (between the flag and shopping cart icons).
- Select your video, then click “Insert 1 item.” This will embed your video in the conversation.
- Under the video, paste the URL to your video.
- You’re done! 

You can see the Teaching team example in Sakai. 

## Presentation comments 

Each student will be assigned 2 presentations to watch. [Click here](https://prodduke-my.sharepoint.com/:x:/g/personal/mt324_duke_edu/ES0ECPUhluBNqTJgeJkR8q8BsCHfmthaPPWruhda8Vp_cA?e=uo1FcX) to see your viewing assignments. 

Watch the group's video, then click "Reply" to post a question for the group. You may not post a question that's already been asked on the discussion thread. Additionally, the question should be (i) substantive (i.e. it shouldn't be "Why did you use a bar plot instead of a pie chart"?), (ii) demonstrate your understanding of the content from the course, and (iii) relevant to that group's specific presentation, i.e demonstrating that you've watched the presentation. 

You may start posting questions and comments on Wed, Nov 18 at 12a EST. **All questions must be posted by Fri, Nov 20 at 11:59p EST**. 

**<i>This portion of the project will be assessed individually.</i>**

## Project repository

In addition to your Gradescope submissions, we will be checking your GitHub repository. This repository should be contributed to equally by all team members and should include

- RMarkdown files (formatted to clearly present all of your code and results)
that will output the proposal and write-up
- Meaningful README file on the GitHub repository that contains a *codebook*
for relevant variables
- Dataset(s) (in csv or RData format, in a `/data` folder)
- Presentation (if using Keynote/PowerPoint/Google Slides, export to PDF and put in repo, in a `/presentation` folder)

Style and format does count for this assignment, so please take the time to make sure everything looks good and your data and code are properly formatted.

The repository must be finalized by **Tuesday, November 17**.

## Peer teamwork evaluation

You will be asked to fill out a survey where you rate the contribution and teamwork of each team member by assigning a contribution percentage for each team member. Filling out the survey is a prerequisite for getting credit on the team member evaluation. If you are suggesting that an individual did less than  half the expected contribution given your team size (e.g., for a team of four students, if a student contributed less than 12.5% of the total effort), please
provide some explanation. If any individual gets an average peer score 
indicating that this was the case, their grade will be assessed accordingly.


## Additional notes and tips

The project is very open ended. For instance, in creating a compelling 
visualization(s) of your data in R, there is no limit on what tools or 
packages you may use. You do not need to visualize all of the data at once. A single high quality visualization will receive a much higher grade than a large number of poor quality visualizations.

Before you finalize your write up, make sure the printing of code chunks is turned off with the option `echo = FALSE`. In addition to code chunks, ensure all messages are turned off with the options `warning = FALSE` and `echo = FALSE`. 

Finally, pay attention to details in your write-up and presentation. Neatness, coherency, and clarity will count.


### Tips

- Ask questions if any of the expectations are 
unclear.

- *Code*: In your write up your code should be hidden (`echo = FALSE`) so that your document is neat and easy to read. However your document should include all your code such that if I re-knit your Rmd file I should be able to obtain the results you presented. 
  - **Exception:** If you want to highlight something 
specific about a piece of code, you're welcome to show that portion. 
- Merge conflicts will 
happen, issues will arise, and that’s fine! Commit and push often, and ask questions when stuck.
- Make sure each team member is contributing, both in terms of quality and quantity of contribution (we will be reviewing commits from different team  members).
- All team members are expected to contribute equally to the completion of this assignment and group assessments will be given at its completion - anyone judged to not have sufficient contributed to the final product will have their grade penalized. While different teams members may have different backgrounds and abilities, it is the responsibility of every team member to understand how and why all code and approaches in  the assignment works.

### Grading summary

Grading of the project will take into account the following:

- Content - What is the quality of research and/or policy question and relevancy 
of data to those questions?
- Correctness - Are statistical procedures carried out and explained correctly?
- Writing and Presentation - What is the quality of the statistical presentation, 
writing, and explanations?
- Creativity and Critical Thought - Is the project carefully thought out? Are the 
limitations carefully considered? Does it appear that time and effort went into 
the planning and implementation of the project?

A general breakdown of scoring is as follows:

- *90%-100%*: Outstanding effort. Student understands how to apply all statistical 
concepts, can put the results into a cogent argument, can identify weaknesses in 
the argument, and can clearly communicate the results to others.
- *80%-89%*: Good effort. Student understands most of the concepts, puts together 
an adequate argument, identifies some weaknesses of their argument, and communicates 
most results clearly to others.
- *70%-79%*: Passing effort. Student has misunderstanding of concepts in several 
areas, has some trouble putting results together in a cogent argument, and communication 
of results is sometimes unclear.
- *60%-69%*: Struggling effort. Student is making some effort, but has misunderstanding 
of many concepts and is unable to put together a cogent argument. Communication 
of results is unclear.
- *Below 60%*: Student is not making a sufficient effort.

## Late work policy

**There is no late work accepted on this project.** Be sure to turn in your work early to avoid any technological mishaps.

## Formatting + communication 

### Suppress Code, Warnings, & Messages



- Include the following code in a code chunk at the top of your .Rmd file to suppress all code, warnings, and other messages. Use the code chunk header `{r set-up, include = FALSE}` to suppress this set up code. 


```r
knitr::opts_chunk$set(echo = FALSE,
                      warning = FALSE, 
                      message = FALSE)
```








