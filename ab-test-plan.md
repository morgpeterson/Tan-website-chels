# A/B Test Plan: Tanz by Chels Homepage Call-to-Action

## Page and element being tested

The test will use the Tanz by Chels homepage:

- Version A (current): https://morgpeterson.github.io/Tan-website-chels/
- Version B (test version): a duplicate of the homepage with only the hero button wording changed.

The one element being changed is the wording of the main button in the hero section.

- **Version A:** “Explore Spray Tanning”
- **Version B:** “View Spray Tan Services & Pricing”

All other page content, layout, images, colors, links, and design will stay the same. Version B will be published as a separate page with a `noindex` tag and will be left out of `sitemap.xml` so it does not compete with Version A in search results.

## Hypothesis and reasoning

I predict that Version B will lead to a higher percentage of visitors saying they would click the main button than Version A. The wording “View Spray Tan Services & Pricing” explains more clearly what visitors will find after clicking. Someone comparing spray tan options may be more interested in a button that specifically mentions services and pricing than the more general wording “Explore Spray Tanning.” This test will show whether the clearer wording makes the next step more appealing to the target audience.

## Model and visitor persona

Every trial will use **ChatGPT GPT-6** with the same settings. Each trial will take place in a new conversation with no memory of earlier trials. The model will not change during the experiment.

The persona will be the same for every trial: a University of Iowa student who lives in Iowa City and is considering getting a spray tan for an upcoming event. The student is comparing options and cares about understanding the services and prices before deciding.

## Exact prompt

The following prompt will be used word for word for every trial. Only the webpage address will change to show the assigned version.

> You are a University of Iowa student living in Iowa City who is considering getting a spray tan for an upcoming event. You are comparing options and care about understanding services and prices before deciding. Visit and review this webpage: [INSERT THE ASSIGNED VERSION'S URL]. Based only on the information on the page, would you click the main button in the hero section to learn more about the spray tan services? Answer YES or NO, followed by one sentence explaining your decision. Do not assume information that is not shown on the page.

## Random assignment

There will be 100 total trials. Before running any trials, I will create a list of 100 assignments using a random number generator, with 50 assigned to Version A and 50 assigned to Version B. I will save the assignment list before collecting responses. Each trial will use a fresh conversation, the same model, the same settings, and the exact prompt above. The only difference between trials will be the assigned webpage version.

## Primary outcome and measurement

The primary outcome will be whether the AI visitor says **YES** or **NO** when asked if they would click the main hero button. Each trial will count as one response. I will record the trial number, assigned version, YES/NO answer, and the model's one-sentence explanation in a spreadsheet. The primary measure will be the percentage of YES responses in each version.

## Sample size and expected completion date

I will complete 50 trials for Version A and 50 trials for Version B, for 100 trials total. I plan to launch the test no later than November 17, 2026, and finish collecting all 100 responses by November 24, 2026. I will not stop early based on the results.

## Comparison and decision rule

I will compare the percentage of YES responses for Version A with the percentage for Version B and calculate the percentage-point difference (Version B minus Version A). I will use a two-proportion test at the 0.05 significance level to evaluate whether the difference could reasonably be due to chance. A higher YES percentage for Version B, with a statistically significant difference, would support the hypothesis. If the difference is small or not statistically significant, I will report that the test did not provide clear evidence that the new wording performed better. I will report all 100 trials, including responses that do not support the hypothesis.

## Limitation

This experiment measures how AI-generated visitors respond to the page, not how real customers behave. The results can help compare the clarity and appeal of the two button labels, but they cannot prove that real Iowa City customers would click the button or book a spray tan.
