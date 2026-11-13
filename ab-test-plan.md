# A/B Test Plan – Hawkeye Performance

## 1. Page and Element Being Tested

This experiment will test the pricing presentation on the Hawkeye Performance homepage. Specifically, it will examine whether visitors are more likely to consider booking training when pricing and available options are displayed directly on the homepage instead of being accessed through an "Explore Pricing" button.

## 2. Version A and Version B

**Version A – Button-Based Pricing**

The homepage will display an "Explore Pricing" button underneath the main homepage title and supporting text. Visitors must click the button to view the available training options and prices.

**Version B – Direct Pricing Exposure**

The homepage will display the available training options and their prices directly underneath the main homepage title and supporting text. Visitors will not need to click another button to view pricing.

Both versions will contain the same training options, prices, headline, supporting text, images, colors, and overall branding. The only difference will be how visitors access the pricing information.

## 3. Hypothesis

I believe Version B will generate a higher percentage of positive responses because displaying prices and training options immediately makes the information easier to access. Potential customers may be more likely to consider booking when they can quickly understand the available options and costs without taking an additional step.

## 4. AI Visitor and Testing Prompt

Each trial will use a new AI conversation with no memory of previous trials.

**AI model:** ChatGPT GPT-6. The same model and settings will be used for all trials.

**Visitor persona:** A high school athlete living in the Iowa City area who participates in school sports and is interested in improving athletic performance outside regular team practices.

**Exact prompt:**

"You are a high school athlete living in the Iowa City area. You participate in school sports and are interested in improving your athletic performance outside of regular team practices. You are considering finding a local training facility to help you improve.

Review the following website homepage as if you were a potential customer. Consider the available training options, pricing, and how easy it is to understand what the facility offers. Based on the homepage, would you take the next step toward booking a training session or contacting the facility? Answer YES or NO, followed by one sentence explaining your decision.

[INSERT VERSION A OR VERSION B HOMEPAGE CONTENT HERE]"

The prompt will remain exactly the same for every trial. Only the homepage version will change.

## 5. Assignment and Randomization

There will be 100 total AI visitor trials: 50 assigned to Version A and 50 assigned to Version B. Before testing begins, a randomized list of all 100 assignments will be created. Each trial will use a fresh conversation, and the assigned version will be recorded.

## 6. Primary Outcome

The primary outcome will be whether the AI visitor says they would take the next step toward booking a training session or contacting the facility.

Responses will be recorded as:
- YES = 1
- NO = 0

The same outcome will be measured for every trial.

## 7. Sample Size and Timeline

The experiment will include 50 trials for Version A and 50 trials for Version B, for a total of 100 trials. The experiment plan will be committed to GitHub before data collection begins. All 100 trials will be completed before the final analysis.

## 8. Analysis

The YES response rate for each version will be calculated by dividing the number of YES responses by 50. The difference between the two rates will be compared using a two-proportion statistical test. If expected counts are too small, Fisher's exact test will be considered.

The hypothesis will be supported if Version B has a higher YES response rate and the difference is statistically significant. If the results are not statistically significant, that will be reported honestly.

## 9. Limitations

Because the experiment uses AI visitors instead of real customers, the results may not fully represent actual customer behavior. AI responses can help evaluate the clarity and accessibility of pricing, but they cannot perfectly predict real clicks, purchases, or booking decisions.

