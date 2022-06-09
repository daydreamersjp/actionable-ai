# actionable-ai
Actionable AI

- Actionable AI is supposed to be a sibling of Explainable AI. The explain of ML results will not necessarily suggest the actions:
  - Explainable AI is like "Your loan application was rejected. The first reason is that your income is low. The second is your remaining morgage loan is still too high. The third..."
  - Actionable AI is like "We can approve your re-application when your income exceed 100,000 USD and your morgage loan is less than 50,000 USD."

- DiCE https://qiita.com/OpenJNY/items/ef885c357b4e0a1551c0
  - https://www.microsoft.com/en-us/research/blog/open-source-library-provides-explanation-for-machine-learning-through-diverse-counterfactuals/
  - https://www.microsoft.com/en-us/research/project/dice/publications/

- Pricing model -> avoiding population bias by stratifying 1) by segment labels (e.g. age, gender, past purchase freqency ...), 2) by segment score (score given by a regression model price~age+gender+frequency of past sales...)
