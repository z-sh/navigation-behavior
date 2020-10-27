# Navigation Behavior
This repository contains all material necessary to replicate our studies related to analysing developers' navigation strategies. In addition, we provide acquired raw data, processed csv files, and the statistical analysis.

# Project 1 - Code Navigation Behavior - 2019
Zohreh Sharafi, Ian Bertram, Michael Flanagan, and Westley Weimer. Eyes on code: Astudy on developers’ code navigation strategies. InTransactions on Software Engineering(TSE), pages 1–13. IEEE, 2020
DOI: 10.1109/TSE.2020.3032064

## Paper Abstract
What code navigation strategies do developers use and what mechanisms do they employ to find relevant information? Do their strategies evolve over the course of longer tasks?  Answers to these questions can provide insight to educators and software tool designers to support a wide variety of programmers as they tackle increasingly-complex software systems.
However, little research to date has measured developers' code navigation strategies in ecologically-valid settings, or analyzed how strategies progressed throughout a maintenance task. We propose a novel experimental design that more accurately represents the software maintenance process in terms of software complexity and IDE interactions.
Using this framework, we conduct an eye-tracking study (n=36) of realistic bug-fixing tasks, dynamically and empirically identifying relevant code areas. We introduce a three-phase model to characterize developers' navigation behavior supported by statistical variations in eye movements over time. We also propose quantifiable notion of "thrashing" with the code as a navigation activity. We find that thrashing is associated with lower effectiveness. Our results confirm that the relevance of various code elements changes over time, and that our proposed three-phase model is capable of capturing these significant changes. We discuss our findings and their implications for tool designers, educators, and the research community.

## Blueprint
DOI: 10.1109/TSE.2020.3032064

## Replication Package
### Stimuli Description and Task Information
We use an open-source implementation of the game, [MineSweeper](https://github.com/KnightMiner/MineSweeper/), available on GitHub.
It is written in Java and it has 1.2 KLOC across 10 files.

### Environment and Plugins
Participants worked on the project using Eclipse IDE. We installed the following plugin:
* [iTrace](http://www.i-trace.org/) to support scrolling and switching between files while recording eye-movements data.
* [fluorite](https://github.com/yyoon/fluorite-eclipse/) to record users' IDE interaction data.


### Task Description
| ID | Description | 
| --- | --- |
| Task-1 | When you start theMineSweeperprogram, if you click on "New Game" button, it will crash. |
| Task-2 | MineSweeper  has  3  difficulty  levels.  The  size  of  the  board  and  the number  of  the  mines  are  different  for  each  level.  Sometimes,  we  endup having a smaller number of mines in the game. For an easy game,we want to have 10 mines, but sometimes it is 9, 8, or even less. |


### Data
The pre-processed data with all the information on phases are available in "pre-processed-data" folder. Please contact "zohrehsh@umich.edu" for access to the raw data.
The csv files that we used for final analysis are available in "summary-data" folder.

| **File** | **Description** | 
| --- | --- |
| raw-data | raw eye-gaze data of all participants.
| FinalSurvey.csv | Summary of all survey results (demographics, socioeconomic status, autism spectrum score, and answers to pre-questionnaires, post-questionnaire, and [SPANE](https://www.psytoolkit.org/survey-library/spane.html) questionnaires. |
| phase_stats_Final.csv |  Fixation data per phase, per participant. |
| Dist_Art_Final.csv | Attention distribution data per phase, per participant. |
| fluorite_log_reports.csv | Fluorite data per phase, per participant. |

# Contact Us
For more information or if you have any questions/feedbacks, please contact Zohreh Sharafi (zohreh.sharafi@ieee.org).

