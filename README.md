# RedWine-Quality

## The Assignment:

**Data**
The data may be taken from an existing source or be data the group collected themselves. The data should
include a well-defined response variable and at least three potential explanatory variables. There should be
some motivation for analyzing the data.
Note: avoid simulated data or data that focus on variables computed from some known algorithm (e.g.,
university scores computed from man-made metrics). Motivation for analyzing such data are typically weak.

**Interim proposal**
An interim proposal is due the evening of Monday, March 3. The interm report should be no longer than
one page in length (including tables and figures; excluding references, if any). The font size should be 10pt
at a minimum. The interim report should include the following information:
1. The source from which you obtained the data.
2. A brief description of all potentially relevant variables in the data (such as when, where, how, units,
and any other important information). Similar variables may be described together.
3. The research question and other motivation for analyzing the data, and any brief background or context
necessary to understand the motivation.
• As this is a statistics course, the research question should focus on inference.
• The research question should address 1–2 specific relationships of interest as opposed to “explore
which of our variables are related to the response”.
4. An overview of who in your group will do what. This does not need to be in detail but should broadly
outline each member’s responsibilities. It is fine if responsibilities change over the course of the project

**Final report**
The final report is due the evening of Thursday, April 17. The target audience of the report is someone
who is knowledgeable in statistics, but who is unfamiliar with the data and its context. The report should
comprise the following sections (see the rubric at the end of this document for more details):
1. Introduction: Describe the data in detail, with specifics on what was recorded and how, along with the
motivation behind the analysis.
2. Analysis: Present suitable visualizations and summaries of the data. Identify and interpret any notable
observed features. Discuss how those features has informed your approach to the statistical analysis.
Explain and apply the chosen statistical methodology to address the motivating question(s) of interest.
3. Conclusion: Interpret and discuss findings from the analysis along with any other pertinent comments.
Address the initial research question(s).
4. Appendix : Include any other relevant information, plots, or tables in this optional section. Note that
the grader is not obligated to read this section, and so any content that is to be graded should be
within the main body of the report.
The report should not exceed eight pages in length (including tables and figures; excluding references and
appendix sections, if any). The font size should be 10pt at a minimum. Each group is to submit a PDF
copy of their final report on Gradescope. The R script and data files are to be submitted on Canvas. See
Canvas for details.

## The dataset: 

**Input variables (based on physicochemical tests)**
1 - fixed acidity \
2 - volatile acidity \
3 - citric acid \
4 - residual sugar \
5 - chlorides \
6 - free sulfur dioxide \
7 - total sulfur dioxide \
8 - density \
9 - pH \
10 - sulphates \
11 - alcohol \

**Output variable (based on sensory data)**
12 - quality (score between 0 and 10) \
The plan: Logistic regresson with quality above 7 (>=7) being 1, less than 7 (<7) being 0.  

