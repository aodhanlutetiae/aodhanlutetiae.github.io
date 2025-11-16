---
title: Use an LLM to monitor the Employment Tribunal
date: 2025-08-22
permalink: /posts/2025/08/blog-post-21/
tags:
  - LLMs
  - Employment tribunal
---

The Employment Tribunal hears claims from people who say an employer "has treated them unlawfully". 

The rulings for Great Britain are published online and there are more than 120,000 of them (since 2016). This collection of PDFs was used very effectively a few years ago by Bloomberg journalists for [How corporate Britain hides thousands of sex discrimination cases](https://www.bloomberg.com/graphics/2019-uk-sexual-discrimination-settlements/).

Can an LLM review a large number of these documents and point to possible stories? And can it do it *offline*, since the next batch of PDFs might not be something we want to work on confidentialy and not upload to an LLM chatbot platform?

I collected the rulings for 200 cases of alleged age discrimination at work in England & Wales in 2025, which generated 309 PDFs (some rulings have more than one document). Can an LLM look at these for possible leads?

I supplied the following prompt as context (after some early results that were far too general): 

"This is a collection of rulings from the Employment Tribunal in England and Wales in 2025. They all pertain to alleged age discrimination in the workplace. What points might be useful leads for journalists? Be concise and specific. Avoid generalities since we know what the documents are about. We are looking for what is unusual, widespread or newsworthy."

Here are the suggestions the LLM made, after I ran the query a few times, with some comments on how valuable the suggestion appears.

*
**Age-related harassment in universities**: 
One ruling (Case No: 2408905/2023) involves a claimant who alleged age-related harassment at Lancaster University. This might be a useful lead to explore if there are patterns or systemic issues with age-based discrimination in higher education institutions.*

— The [case](https://assets.publishing.service.gov.uk/media/684a9b3824224d02f84137c8/Mrs_R_Wilkinson_v_Lancaster_University_-_2408905_2023_-_Judgment.pdf) is easy to find with the number. There seems to be little value however in the case, which lapsed after the claimant didn't pay "the deposits ordered".

**Striking out unfair dismissal claims due to lack of deposits**: In another ruling (Case No: 2408905/2023), the claimant's unfair dismissal, age discrimination, and harassment-related claims were struck out due to failure to pay required deposits. This could be a lead worth exploring if there are concerns about the process or fairness in Employment Tribunal proceedings.
*This refers to the same case. Worth at least trying to understand what "deposits" are in this context*

**Direct age discrimination claims dismissed**: Many of the rulings involve direct age discrimination claims being dismissed. Journalists might want to investigate what factors contributed to these dismissals and whether there are common themes or patterns among the rejected claims. These leads could provide interesting stories on age-related workplace issues, Employment Tribunal procedures, or possible systemic problems that need to be addressed.
*Little value here*

**Age threshold variability**: Notable that one case (Case No: 3300980/2021) has a pleaded age threshold of 40, which is significantly higher than the typical retirement age of 65-68 in the UK.
*The [case](https://www.gov.uk/employment-tribunal-decisions/miss-t-donaldson-and-mrs-t-de-mello-v-british-airways-plc-3300980-slash-2021-and-3301038-slash-2021) here*

**Unusual comparator selection**: In some cases (e.g., Case Nos: 3301038/2021), the respondent accepts that part-time workers are the correct comparator for full-time employees, which could indicate a shift in employment practices or policies.
*This is another part of the same case...*

**Increased scrutiny of retirement age policies**: With multiple cases related to alleged age discrimination, there may be an opportunity to explore whether employers' retirement age policies are being challenged more frequently and why.
*Unhelpful*

**Growing awareness of indirect age discrimination**: Some cases (e.g., Case No: 2408905/2023) involve allegations of indirect age discrimination, which could indicate a growing understanding among employees of the different forms of age-related unfair treatment in the workplace.
*This is the first case again, involving Lancaster University*

**Impact of COVID-19 on employment practices and policies**: The Employment Tribunal rulings may provide insights into how the pandemic has influenced employers' decisions regarding retirement ages, part-time work, or other aspects of employment that can contribute to age discrimination. These leads are specific to the collection of Employment Tribunal rulings from 2025 and highlight potential stories related to age discrimination in the workplace.
*Unhelpful*

**Unsuccessful age discrimination claims**: Many of the cases have been dismissed due to a lack of evidence or failing to meet the burden of proof. This could be an opportunity to explore the common pitfalls and challenges in bringing age discrimination claims.
*Unhelpful*

**Age-related harassment**: Several cases involve allegations of age-related harassment, which may not be widely reported on. Investigating the prevalence and impact of this type of discrimination could lead to a newsworthy story.
*Is age-related harassment worth looking into?*

**Inadequate tribunal processes**: Some cases highlight issues with the Employment Tribunal's procedures, such as delays or difficulties in obtaining justice. This could spark a discussion about improving the system.
*May be worth looking at*

**Unusual case scenarios**: One ruling involves a claimant seeking to amend their claim after a preliminary hearing. Another case highlights the potential for age-related discrimination in benefit packages. These unusual scenarios might make for an interesting and unique story.
*May be worth looking at*

**Lack of judicial resources**: A few cases were adjourned due to a lack of judicial resources, which could be an opportunity to explore the impact of funding constraints on the Employment Tribunal's ability to deliver justice.
*May be worth looking at*
