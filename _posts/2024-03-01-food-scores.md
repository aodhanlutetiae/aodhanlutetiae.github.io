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

<img src="/images/4_food_safety_picture.jpg" alt="drawing" width="300"/>

*A “da” rating of 4 on an eatery window in Wales. Food hygiene here is “good”* 

The technology predicted two things: the hygiene rating of a food outlet that was waiting for inspection, and the probability that it would be broadly “non-compliant” (a 0, 1 or 2 rating) or “compliant” (a 3, 4 or 5 rating). 

<img src="/images/user_guide_p8.jpg" alt="drawing" width="600"/>

*Screenshot of (part of) how the tool might respond when asked about a specific local authority, with the names of the area's food outlets removed*

The model was to be used to identify which cases were most urgent, leaving local authority inspectors to establish the actual rating after a visit.

The code used to train the computer model was released in response to a Freedom of Information request along with an outline of the kinds of data that, once supplied to the computer system, would generate the two predictions.

A more detailed version of the machine’s response shows not just if the outlet is predicted to get a compliant rating (3-4-5) or non-compliant rating (0-1-2) but how *likely* it is to fall into a compliant category.

<img src="/images/user_guide_p9.jpg" alt="drawing" width="800"/>

*Part of a response, showing how likely it is that food outlets will get a higher, ‘compliant’ score*

This technology was first described on a government platform to list algorithms that are used in the public sector: the [Algorithmic Transparency Recording Standard](https://www.gov.uk/government/publications/algorithmic-transparency-template). This pilot platform was launched in late 2021 by two government offices that work on data. The details of just [six algorithms](https://www.gov.uk/government/collections/algorithmic-transparency-reports) were published the following year but since October 2022, nothing. 

When asked, the Department for Digital, Culture, Media & Sport said it intends “to update the list soon”.

**Methodology**

