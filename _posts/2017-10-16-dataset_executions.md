---
layout: post
title: "Data on 'Executions in the United States,' and what it can tell us about slave revolts"
date: 2017-10-16
---
As a continuation of our unit on data, I looked for a dataset that was in line with some of my research interests and proceeded to analyze it. I discovered that Northeastern subscribes to ICPSR, the Inter-university Consortium for Political and Social Research, so I made an account and 
searched for data on slavery. I found a study called <a href="https://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/08451">Executions in the United States, 1608-2002: The ESPY file</a>, which had a wealth of interesting information
about execution and various social variables. I downloaded the study's TSV file and sought to analyze its contents.

This exercise drew my attention to a feature in Google spreadsheets which generates automatic graphs from datasets. I saw potential in this feature and would return to it in the future.
However, for my purposes in this exercise, I found that the automatic graphs did not generate information that was of much interest to me--either they didn't use variables
that I wanted to look at, or they didn't show outliers that were significant to me. This was probably due to the fact that the dataset in question measures 21 different variables. There are a lot of data in this study, and many different ways of representing it all.

Rather than chart the data using Google, then, I decided to sort the data myself by numeric field in order to find interesting trends. I also
decided to take advantage of a feature offered by some ICPSR studies, which is a crosstab/frequency generator that allows users to build charts and graphs by selecting for certain variables.

One of the more intriguing discrepancies I saw when sorting the data by numeric field was in the race of offender for the crime of slave revolt. Predictably, most of those who were executed for this crime were black--however, this amounted to 90.6%, meaning that 9% of the offenders were white and 0.4% (representing one individual) were Native American. Investigating these outliers yielded interesting insights. 

<table class="w3-table">
<tr>
  <th>V5 (Race)</th>
  <th>V10 (Crime) 8 (Slave revolt)</th>
  <th>Row total</th>
</tr>
<tr>
  <td>1 (White)</td>
  <td>9.0% (24)</td>
  <td>9.0% (24)</td>
  </tr>
  <tr>
  <td>2 (Black)</td>
  <td>90.6% (251)</td>
  <td>90.6% (251)</td>
  </tr>
  <tr>
  <td>3 (Native American)</td>
  <td>0.4% (1)</td>
  <td>0.4% (1)</td>
 </tr>
  <tr>
    <td>Total</td>
    <td>100.0% (277)</td>
    <td>100.0% (277)</td>
  </tr>
</table>

<div id="images">
        <img src="https://image.ibb.co/mTxn5m/revolt.png">
        <div class="caption">A chart and bar graph generated through ICPSR's crosstab/frequency interface.</div>
   </div>

In accordance with an organized event like a slave revolt, several individuals were executed for this crime in the same place and at the same time. In 1741, four white people were executed in New York for participating in a slave revolt--their occupations are listed as a bar owner, a housewife (presumably the bar owner's wife, as they share a last name), a bar maid, and a priest. In contrast, twenty white people were executed in 1712, all of whom are listed as "slave" under their occupation. It is interesting to note the difference between white slaves in revolt versus free whites aiding slaves in revolt, in the same state, and mere decades apart. This raises questions that I would like to investigate further, such as when the practice of keeping white people as indentured servants died out and what slavery was like in New York (I know it was one of the last northern states to ban it); it would also be interesting to look into local slave revolts as opposed to those which have been highly publicized (e.g. Nat Turner's rebellion).

Datasets like these can point to previously unrecognized trends and help researchers generate new questions and ideas. Repositories of these datasets, like ICPSR, can be an important resource in the arsenal of a historian.

The full dataset, along with my analysis, can be viewed <a href="https://docs.google.com/spreadsheets/d/1vrVzto9qc7Braf_1cszWQOMCEHUvEKcRH7el1RqDb50/edit?usp=sharing">here</a>.
