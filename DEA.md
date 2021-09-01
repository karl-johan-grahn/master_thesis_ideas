# Data Envelopment Analysis (DEA) for software team efficiency analysis
Comparing efficiency of organizations such as schools, hospitals, banks, retails stores are quite common, yet comparing efficiency of software teams are rarely done.

Data Envelopment Analysis (DEA) was first proposed by [Charnes, Cooper, and Rhodes in 1978](https://www.sciencedirect.com/science/article/abs/pii/0377221778901388). It analyzes the relative performance of a group of similar organizations. How is an individual software team performing in comparison with others? A simple expression of efficiency is weighted outputs divided by weighted inputs. The DEA approach for determining the suitable weights is to find the set of weights for team X that maximises that particular team's efficiency score. Those same weights are then used to calculate the efficiency score for the other teams in the data set. Clearly those weights may not be the optimal weights for the other teams, however, by looking at the efficiency scores calculated, we can determine the team X's efficiency relative to the other teams. The analysis can then be repeated for the other teams in the data set to assess their relative efficiency.

The 'envelopment' part of DEA comes from the fact that the efficient units create an 'envelope' around the data set.

The thesis is to investigate:
- How can DEA be used to measure efficiency of teams at Sinch?
- What are the benefits and disadvantages of measuring efficiency through DEA?
- How should teams be defined?
- What outputs should be used?
- What inputs should be used?