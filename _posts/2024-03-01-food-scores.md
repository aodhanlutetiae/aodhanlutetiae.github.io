---
title: 'Algorithm to suggest food inspections abandoned'
date: 2024-03-01
permalink: /posts/2024/03/blog-post-19/
tags:
  - algorithms
  - councils
  - food 
---

UK food inspectors have abandoned plans to use an algorithm in part of their food hygiene rating system after a £100,000 trial. 

Fifteen local authorities took part in the six-week pilot in 2022. But in the end many local authorities found their own solutions to a post-Covid food inspection backlog, and the Food Standards Agency (FSA) said the automation raised too many ethical questions.

<img src="/images/4_food_safety_picture.jpg" alt="drawing" width="400"/>

*A “da” rating of 4 on an eatery window in Wales. Food hygiene here is “good”* 

The technology predicted two things: the hygiene rating of a food outlet that was waiting for inspection, and the probability that it would be broadly “non-compliant” (a 0, 1 or 2 rating) or “compliant” (a 3, 4 or 5 rating). 

<img src="/images/user_guide_p8.jpg" alt="drawing" width="600"/>

*Screenshot of (part of) how the tool might respond when asked about a specific local authority, with the names of the area's food outlets removed*

Faced with a simple but pressing question after Covid, “Who should we inspect first?” the FSA paid the company Cognizant to build the technology. The model was to be used to identify which cases were most urgent, leaving local authority inspectors to establish the actual rating after a visit.

The code used to train the computer model was released in response to a Freedom of Information request along with an outline of the kinds of data that, once supplied to the computer system, would generate the two predictions.

A more detailed version of the machine’s response shows not just if the outlet is predicted to get a compliant rating (3-4-5) or non-compliant rating (0-1-2) but how *likely* it is to fall into a compliant category.

<img src="/images/user_guide_p9.jpg" alt="drawing" width="800"/>

*Part of a response, showing how likely it is that food outlets will get a higher, ‘compliant’ score*

This technology was first described on a government platform to list algorithms that are used in the public sector: the [Algorithmic Transparency Recording Standard](https://www.gov.uk/government/publications/algorithmic-transparency-template). This platform was launched as a pilot in late 2021 by two government offices that work on data. 

The details of just [six algorithms](https://www.gov.uk/government/collections/algorithmic-transparency-reports) were published the following year and publication resumed early this year with the details of [an algorithm developed](https://www.gov.uk/government/publications/cabinet-office-automated-digital-document-review) for the Cabinet Office.

The FSA technology was ultimately shelved because the Agency decided that there were "ethical concerns" and that data on demographics and the type of food prepared "could result in biases for certain types of businesses". 


**How it works**

<img src="/images/code_ext.jpg" alt="drawing" width="600"/>

*Some of the code that trained the model from existing data and generated predictions for new data*




**Methodology**

The government platform was brought to my attention by a talk at [Open Data Camp 2023](https://www.odcamp.uk/) in Wolverhampton. The Transparency Recording Standard makes available [an outline of the technology](https://www.gov.uk/government/publications/food-standards-agency-food-hygiene-rating-scheme-ai/food-standards-agency-food-hygiene-rating-scheme-ai).

After an FOI request, I was given an outline of the variables used in building the technology and the code used to build the computer model. A second FOI request returned two pieces of documentation: a user manual and an Ethical AI framework.
