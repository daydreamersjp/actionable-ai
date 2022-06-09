# Actionable AI

- Actionable AI is supposed to be a sibling of Explainable AI. The explain of ML results will not necessarily suggest the actions:
  - Explainable AI is like "Your loan application was rejected. The first reason is that your income is low. The second is your remaining morgage loan is still too high. The third..."
  - Actionable AI is like "We can approve your re-application when your income exceeds 100,000 USD and your morgage loan is less than 50,000 USD."
  - It will give an exact counter sample (i.e. "rejection" -> "approval") with the least changes against the possible controlable factores with controlable combination. (anti-pattern is like "Your are a bachelor now but if you can be a PhD within this year, you will be approved.")
  - It will involved in the optimization (i.e. minimizing the changes of the factors) with constraints (i.e. avoid un-attainable combination of changes), and causality relationship (i.e. the change actually has to move things towards the expected direction).


- Two types of actionable samples:
  - Example-based. Give another sample data in the traing data that is closest to the query data (=the data we want to find the action for), also within the constraints, but gives the opposite outcome.
  - Simulation-based. Find the virtual data, not from the traing data that is closest to the query data, also within the constraints, but gives the opposite outcome.

- DiCE https://qiita.com/OpenJNY/items/ef885c357b4e0a1551c0
  - https://www.microsoft.com/en-us/research/blog/open-source-library-provides-explanation-for-machine-learning-through-diverse-counterfactuals/
  - https://www.microsoft.com/en-us/research/project/dice/publications/



### Memo about something else
- Pricing model -> avoiding population bias by stratifying 1) by segment labels (e.g. age, gender, past purchase freqency ...), 2) by segment score (score given by a regression model price~age+gender+frequency of past sales...)
