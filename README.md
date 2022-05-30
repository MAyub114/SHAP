## What are SHAP Values?
Shap values are a tool that are notable for being able to explain specific predictions from your model. They do this by quantifying the contributions of each individual feature.

## How do they do this?
The shapley value associated with a feature is the average of its marginal contributions. That is a dense definition so let's start breaking it down. Thanks to this excellent medium post for helping me understand this concept.

Say Alex, Bill and Connie are selling lemonade in this slightly contrived examples. Altogether they can sell 100$ worth of lemonade. However they are all a little greedy so instead of splitting the money evenly they want to figure out how much each of them contributed to the 100 dollars in sales so they can figure out how much they each really deserve.

Each of their respective 'Shapley Values' would tell them their earned value and correspond to on average how much more value is gained when they are a member of the team. If you are more math minded you might be wondering how do exactly quantify the marginal contribution. Unfortunately there is no general purpose way to get these marginal contributions and it depends on what sort of 'game' in the game theory sense you are particiapting in.
