
# A/B Test Protocol: Bangkok on a Budget

**Protocol created:** November 23, 2026  
**Original A/B test plan:** Submitted separately  
**Testing status:** Scheduled to begin November 23, 2026

## 1. Purpose

This document supplements the original A/B test plan. It clarifies the actual homepage headlines and establishes the procedure that will be followed when conducting the experiment.

The original plan described Version A as "Bangkok on a Budget." However, the actual homepage headline in the website code is "Bangkok Travel Tips for First-Time Visitors." The experiment will use the actual existing homepage as Version A rather than changing the original website after the plan was submitted.

## 2. Versions Being Tested

The experiment will test whether changing the homepage headline affects an AI visitor's interest in exploring the website's itinerary page.

- **Version A:** "Bangkok Travel Tips for First-Time Visitors."
- **Version B:** "Plan Your First Bangkok Trip Without Breaking the Bank."
- **Element being tested:** The main homepage headline.
- **Version A URL:** https://jsadoski7.github.io/Bangkok-Budget-Travel/
- **Version B URL:** https://jsadoski7.github.io/Bangkok-Budget-Travel/index-b.html

The visible homepage content, navigation, links, and design will remain the same. The only intended visible difference is the main headline.

Version B includes a noindex instruction so search engines are instructed not to index the experimental page. This does not change the visible homepage content.

## 3. AI Visitor and Model

AI visitors will represent college students planning their first trip to Bangkok, Thailand, who have a limited travel budget.

- **AI tool:** ChatGPT
- **Model label:** GPT-6
- **Model version:** No more specific version displayed.
- **Settings:** Default settings. The same settings will be used for every trial.
- **Testing start date:** November 23, 2026
- **Planned final testing date:** November 25, 2026

Each trial will take place in a fresh conversation. No previous trial's responses will be included in a new trial. The same model and settings will be used throughout the experiment.

## 4. Standardized Visitor Prompt

The following prompt will be used for every trial. The only change will be the homepage headline corresponding to the assigned version.

"You are a college student planning your first trip to Bangkok, Thailand. You have a limited travel budget and are looking for helpful information to plan your trip.

Read the following homepage carefully. Based only on the information provided, decide whether you would explore the website's itinerary page to continue planning your trip.

Would you explore the itinerary page?

Answer YES or NO, followed by one sentence explaining your decision.

Homepage:

Brand: Bangkok on a Budget

Main headline: [INSERT THE ASSIGNED VERSION A OR VERSION B HEADLINE]

Supporting text: First-time Bangkok travel starts with a plan. Explore the five guides below to build a trip that fits your schedule and spending goals.

Main button: Explore the budget guide.

Other homepage content:
- Start with your priorities: Decide how many days you have, how much you can spend, and which experiences matter most. Leave room for unexpected expenses.
- Prepare before departure: Check official passport, entry and travel guidance before booking. Requirements can change, so do not rely on an older checklist.
- Plan around neighborhoods: Group nearby activities together to reduce transit time and avoid unnecessary transport costs.
- Trip planning checklist: Choose travel dates and confirm official entry guidance; set a spending limit and contingency fund; plan neighborhoods and routes; pack for the season and planned activities.
- Navigation includes Home, Budget, Packing, Transportation, and Itinerary.
- The homepage includes links to the Budget, Packing, Transportation, and Itinerary guides."

The same prompt wording and homepage information will be used for both versions. Only the main headline will change.

## 5. Random Assignment

Before testing begins, a randomized assignment schedule will be created with 100 total trials:

- 50 assigned to Version A.
- 50 assigned to Version B.

The order of the trials will be randomized before data collection begins. The assignment schedule will be saved and will not be changed based on results.

Each trial will use the version assigned in the schedule.

## 6. Sample Size and Stop Date

The target sample size is 100 completed trials:

- 50 Version A trials.
- 50 Version B trials.

**Predetermined stop date:** November 25, 2026, at 11:59 p.m. Central Time.

Testing will stop when all 100 trials are completed or when the predetermined stop date is reached, whichever comes first. If fewer than 100 trials are completed, the final report will explain the limitation.

Trials will not be removed because their answers are unexpected or inconvenient. Any technical errors or incomplete responses will be documented.

## 7. Data Collection

One row will be recorded for every trial in a spreadsheet.

The spreadsheet will include:

- Trial number
- Assigned version
- Date and time
- AI model used
- Exact prompt used
- YES or NO outcome
- AI visitor's explanation
- Any technical errors or unusual circumstances

The original AI responses will be preserved so the results can be checked.

## 8. Analysis and Decision Criteria

The percentage of YES responses will be calculated separately for Version A and Version B.

Version B will be considered more promising if it has a higher percentage of YES responses. A statistical test will also be used to evaluate whether the observed difference provides evidence of a meaningful difference.

The results will be reported honestly, including if the experiment does not show a clear difference.

## 9. Documentation

This protocol will be committed to the GitHub repository before the first trial begins. The original A/B test plan and its commit history will be preserved.

Any changes to the testing procedure after data collection begins will be documented rather than silently changing the original protocol.
