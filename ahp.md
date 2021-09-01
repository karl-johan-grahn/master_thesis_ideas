# AHP/ANP approach for optimizing decision making in software development
Business decisions should be based on rational analysis but often involve subjective feelings. For example, when hiring someone, the person might be a perfect fit with technical skills, but if the personal attitude is bad, the opportunity is lost. Another example is migrating to a new technology stack - the old stack is out of date and not maintained any longer, so the team has to decide on a new stack. People will weight critera differently, depending on their experience and skills in the different subjective domains. Some might think performance is critical, while some might think tool standardization is more important. The problem is that these subjective feelings are seldom recorded and made part of the decision documentation.

The AHP (Analytic Hierarchy Process)/ANP (Analytic Network Process) was developed by [Prof. Thomas L. Saaty](https://pubsonline.informs.org/doi/abs/10.1287/opre.2013.1197) to help with complex multicritera decision problems. It requires the decision maker to provide judgements about the relative importance of each critera and then specify a preference for each decision alternative using each criterion. The output is a prioritized ranking of the decision alternatives based on the overall preferences expressed by the decision maker.

The benefit of using AHP is that the judgements of the importance of the critera and the preferences for the decision alternatives using each criterion becomes documented. It provides a clearer understanding of the tradeoffs in the decision-making process.

The thesis is to investigate:
- Which type of software decision problems can benefit from AHP/ANP?
- How can ANP help update criteria after additional information is found?
- How can AHP/ANP be applied to group decision making?
- How can it be integrated with ticket systems like Atlassian JIRA?