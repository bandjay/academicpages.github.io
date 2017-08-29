---
title: "Mayo Clinic [ MAY 2017 - AUG 2017]"
collection: publications
permalink: /publications/2016-10-01-paper-title-number-1
---
During the summer I worked as an IT intern at Mayo clinic.There I was responsible to automate the genetic report generation in data pipelines. <br/>
<br/>
Patient Gene Report Automation
<br/>
Tools: Python, Unix, Perl, Selenium, beautiful soup, pptx
<br/>
Aim of this project is to automate patient gene report (.pptx) generation with the use of  gene data coming from various sources such as files, web sites etc., As obtaining gene data from multiple sources, creating a power point gene report is tedious and often gene counselors spend hours in preparing these reports. So through this project I automated pptx document generation using python to save time (~ 20 minutes per report) for gene counselors such that they can spend more time with patients than to worry about making reports manually.
<br/>
Automation pipeline was built in python and software can be run using command line, and pipeline was developed as per the steps below
<br/>
1 .Data extraction: As mentioned, gene data can come from many sources such as catalog files on the unix file system so good amount of unix ,perl scripting was done and integrated into python to pull gene variant data. Also, there are several online web sources for gene information such as OMIM, EXAC, NCBI etc and data from these sources is obtained by web scraping and selenium automation tool was used to capture the necessary screenshots from the web pages.
<br/>
2. Data processing:  Extracted gene data into VCF format files which was mostly text and unstructured so necessary fields were obtained by parsing VCF files using regular expressions and dictionary data structures. And web scraped html pages were parsed using “beautifulsoup” python library.
<br/>
3. Report Generation:  After getting necessary gene information, several user defined functions were implemented to obtain required labels based on existing gene fields. At the end, generated a pptx report with the required labels, text, tables and screenshots using “pptx” python library

<br/>
Git links for more details <br/>
​[flash_ppt](https://github.com/bandjay/flash_ppt)<br/>
