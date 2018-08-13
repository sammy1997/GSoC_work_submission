# Sysbot - GSoC 2018 Final Work Submission

## Student: Sombuddha Chakravarty

### About

Systers being a vibrant open source community, participates in a lot of major 
open source programs throughout the year, like - Outreachy,RGSoC, GCI, GSoC etc.
These programs go on round the year and often even overlap. 

To maintain the quality, the mentors, admins and students try to clean the repositories and 
also at the same time aid the newcomers to get started, and get comfortable with the work flow. 
This becomes really hectic specially when transitioning fom one program to another.
Hence came the idea of Sysbot, which is a Slack-bot integrated with Github to streamline open source workflow.

A bot which was integrated with Slack and Github and could automate and pace up a lot of the work, and reduce load on mentors. 
It could also enforce certain essential practices for open-source, like PRs being sent to unreviewed issues,
or not being linked to issues at all, etc.


Team
------------------

**Admin:** Prachi Manchanda  
**Mentors:** Ramit Sawhney, Sarah Masud, Akshita Aggarwal


Tech Stack
------------------

**Language:** Python 2.7  
**Libraries and Framework:** Flask, Unittest (for testing), NLTK  
**APIs:** Slack Events API, LUIS API (For intent based Classification), Github API  


Timeline
------------------

[Link to approximate timeline](https://docs.google.com/document/d/1b8Ie_KsAVxJPzYq8KWrx9S6NiTEjQcq2YfXzsXyyvCw/edit?usp=sharing)


Work Done
------------------

The following is a list of PRs sent by me during he GSoC period:  

1. [Link](https://github.com/systers/sysbot/pull/4) : Added a gitignore file with standard template for Python
2. [Link](https://github.com/systers/sysbot/pull/5) : Added text file with help links
3. [Link](https://github.com/systers/sysbot/pull/10) : Commonly used help phrases added
4. [Link](https://github.com/systers/sysbot/pull/13) : Added requirements file for creating virtual environment
5. [Link](https://github.com/systers/sysbot/pull/14) : Credential files added and gitignore updated
6. [Link](https://github.com/systers/sysbot/pull/16) : Add not approved label to new issues
7. [Link](https://github.com/systers/sysbot/pull/19) : Added a function to find the stems of words in a sentence
8. [Link](https://github.com/systers/sysbot/pull/22) : Added code style changes to follow Python standards
9. [Link](https://github.com/systers/sysbot/pull/29) : Added first timer welcome message propert
10. [Link](https://github.com/systers/sysbot/pull/30) : Added message file and initial message
11. [Link](https://github.com/systers/sysbot/pull/31) : Added function to recognize if a comment is made by a mentor or not
12. [Link](https://github.com/systers/sysbot/pull/32) : Added feature to get invited to newcomers team via slack
13. [Link](https://github.com/systers/sysbot/pull/34) : Added feature to add approve labels to issues via github comments
14. [Link](https://github.com/systers/sysbot/pull/35) : Added feature to approve tags from slack
15. [Link](https://github.com/systers/sysbot/pull/36) : Added feature to label newly opened PRs
16. [Link](https://github.com/systers/sysbot/pull/37) : Added feature to assign issue from Slack 
17. [Link](https://github.com/systers/sysbot/pull/39) : Added feature to assign issues from Github comments
18. [Link](https://github.com/systers/sysbot/pull/43) : Added feature to claim issues from github
19. [Link](https://github.com/systers/sysbot/pull/44) : Added feature to claim issues from Slack
20. [Link](https://github.com/systers/sysbot/pull/50) : Added feature to stop multiple claims of an issue
21. [Link](https://github.com/systers/sysbot/pull/51) : Added feature for checking coveralls comment
22. [Link](https://github.com/systers/sysbot/pull/53) : Minor changes made in code for errors found during testing
23. [Link](https://github.com/systers/sysbot/pull/55) : Added design doc file for template matching of issues
24. [Link](https://github.com/systers/sysbot/pull/56) : Added feature for opening issues via Slack. Markdown not supported
25. [Link](https://github.com/systers/sysbot/pull/60) : Added feature for comments to be only visible to the commentor
26. [Link](https://github.com/systers/sysbot/pull/64) : Added check for author of issue against issue approval.
27. [Link](https://github.com/systers/sysbot/pull/65) : Added features for unclaiming and unassigning issues
28. [Link](https://github.com/systers/sysbot/pull/67) : Added patch for claim command to accept github username from Slack profile
29. [Link](https://github.com/systers/sysbot/pull/69) : Help slash command
30. [Link](https://github.com/systers/sysbot/pull/70) : Check approval label
31. [Link](https://github.com/systers/sysbot/pull/73) : Added feature to check if PRs are sent to unapproved issues
32. [Link](https://github.com/systers/sysbot/pull/80) : Added feature to check for issue template mismatch
33. [Link](https://github.com/systers/sysbot/pull/83) : Added feature to collect list of PRs which have not been reviewed
34. [Link](https://github.com/systers/sysbot/pull/84) : Solve markdown problem with issue opening from Slack
35. [Link](https://github.com/systers/sysbot/pull/86) : Refactored code to clean up repository
36. [Link](https://github.com/systers/sysbot/pull/87) : Patch for functions
37. [Link](https://github.com/systers/sysbot/pull/88) : Added travis config file
38. [Link](https://github.com/systers/sysbot/pull/91) : Added unit tests. Coverage 49%.
39. [Link](https://github.com/systers/sysbot/pull/95) : Added feature to mention slack teams
40. [Link](https://github.com/systers/sysbot/pull/96) : Auto-deploy and selective testing script
41. [Link](https://github.com/systers/sysbot/pull/97) : Exculded some functions from coverage
42. [Link](https://github.com/systers/sysbot/pull/103) : Answer with projects list
43. [Link](https://github.com/systers/sysbot/pull/104) : Feature to answer FAQs
44. [Link](https://github.com/systers/sysbot/pull/108) : Enhance template check
45. [Link](https://github.com/systers/sysbot/pull/110) : Feature: Check if PR template has been followed
46. [Link](https://github.com/systers/sysbot/pull/113) : Made changes for auto-deployment and fixed reply feature
47. [Link](https://github.com/systers/sysbot/pull/121) : Fixes issue with approve command
48. [Link](https://github.com/systers/sysbot/pull/122) : Tests added for 60 percent coverage
49. [Link](https://github.com/systers/sysbot/pull/125) : Tests added to cover 90% of code
50. [Link](https://github.com/systers/sysbot/pull/131) : Collected, changed and curated event data
51. [Link](https://github.com/systers/sysbot/pull/134) : Added feature to mock event delivery
52. [Link](https://github.com/systers/sysbot/pull/135) : Fixed overlapping language case
53. [Link](https://github.com/systers/sysbot/pull/138) : Feature to add multiple labels using single command with comma separated label names
54. [Link](https://github.com/systers/sysbot/pull/140) : Added feature to automatically change PR labels based on reviews
55. [Link](https://github.com/systers/sysbot/pull/142) : Added feature to view issue content on Slack
56. [Link](https://github.com/systers/sysbot/pull/144) : Updated help message for /sysbot_help command
57. [Link](https://github.com/systers/sysbot/pull/146) : Added encrypted keys and ways to extract them
58. [Link](https://github.com/systers/sysbot/pull/148) : Added a test dictionary for sample workspace
59. [Link](https://github.com/systers/sysbot/pull/151) : Added feature to label issues from Slack. Added tests
60. [Link](https://github.com/systers/sysbot/pull/152) : Approve command versatile
61. [Link](https://github.com/systers/sysbot/pull/158) : Added minor fixes to pass tests and change PR template


Documentation Added
------------------

The following are all docs made by me during the GSoC period:

1. [Link](https://github.com/systers/sysbot/blob/develop/docs/README.md) : Readme having all information on setting up, bot features and getting started.
2. [Link](https://github.com/systers/sysbot/blob/develop/docs/exporting_keys.md) : Guide to handle keys and extract tokens.
3. [Link](https://github.com/systers/sysbot/blob/develop/docs/template_matching_design.md) : Design for template matching feature
4. [Link](https://github.com/systers/sysbot/blob/develop/docs/nlp_explainations.md) : Small explaination on the NLP concepts used.
5. [Link](https://github.com/systers/sysbot/blob/develop/docs/answering_design.md) : Design doc for answering questions.
6. [Link](https://github.com/systers/sysbot/wiki/Function-descriptions) : Function descriptions of each SLack and Github functions written in code.
7. [Link](https://github.com/systers/sysbot/wiki/Commit-Message-Style-Guide) : Commit message style guide.
8. [Link](https://docs.google.com/document/d/1F-b-A2wbA0DCvp0RoR4ZTXQGqIDrW1nReoag2JHxaFs/edit?usp=sharing) : Data collected for bot.

Reports( Wiki and Blogs)
------------

The following are some reports and blogs made by me during the GSoC period:

1. [Link](https://github.com/systers/sysbot/wiki/GSoC-2018-Sombuddha-Chakravarty) : Wiki report.
2. [Link](https://medium.com/@f2016165/journey-to-gsoc18-891bdad6cc42) : Journey to GSoC’18
3. [Link](https://medium.com/@f2016165/community-bonding-period-systers-8a097a15c007) : Community bonding Period
4. [Link](https://medium.com/@f2016165/gsoc18-first-week-of-coding-phase-f9003768c875) : GSoC’18 First Week of Coding Phase
5. [Link](https://medium.com/@f2016165/gsoc18-second-week-of-coding-phase-8db1d32decbc) : GSoC’18 — Second Week of Coding Phase
6. [Link](https://medium.com/@f2016165/gsoc18-third-week-of-coding-phase-5a3f48a3b210) : GSoC’18 — Third Week of Coding Phase
7. [Link](https://medium.com/@f2016165/gsoc18-fourth-week-of-coding-phase-4fb196d062ba) : GSoC’18 — 4th Week of Coding Phase
8. [Link](https://medium.com/@f2016165/week-5-of-gsoc-the-first-evaluations-4d20d6435902) : GSoC’18 — 5th Week of Coding Phase
9. [Link](https://medium.com/@f2016165/week-6-of-gsoc-cd0e6c25ddae) : GSoC’18 — 6th Week of Coding Phase
10. [Link](https://medium.com/@f2016165/week-7-of-gsoc-dd159e1394b5) : GSoC’18 — 7th Week of Coding Phase
11. [Link](https://medium.com/@f2016165/week-8-of-gsoc18-with-systers-3774def90de0) : GSoC’18 — 8th Week of Coding Phase
12. [Link](https://medium.com/@f2016165/week-9-of-gsoc-the-2nd-evaluations-4badb3ba8f4f) : GSoC’18 — 9th Week of Coding Phase
13. [Link](https://medium.com/@f2016165/week-10-of-coding-phase-gsoc18-a10be5869caa) : GSoC’18 — 10th Week of Coding Phase
14. [Link](https://medium.com/@f2016165/week-11-of-coding-phase-gsoc18-77943924d639) : GSoC’18 — 11th Week of Coding Phase
15. [Link](https://medium.com/@f2016165/last-week-of-coding-phase-gsoc18-c258ee70b885) : GSoC’18 — Last Week of Coding Phase

Final Work Demo
-----------
**Video:** [Link](https://www.youtube.com/watch?v=a0_vqdg4-I4)  
**Demo Slides:** [Link](https://docs.google.com/presentation/d/10RhFbBVFWrOCpdmCHc_6VnjouiBK1WrENZBF4HrBJ70/edit?usp=sharing)

