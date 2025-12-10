Media Bias & AI

Tableau links: 

https://public.tableau.com/app/profile/adam.khan3724/viz/FinalProjectAI_17652352940970/Dashboard5?publish=yes

https://public.tableau.com/app/profile/adam.khan3724/viz/FinalProjectAI_17652352940970/Dashboard4

Research Question

How does media bias toward AI differ across business, political, and general interest news outlets in the United States?

Section 0.a: Business Case

As artificial intelligence continues to expand and evolve so too does media coverage of its ongoing developments. Oftentimes, media articles involving artificial intelligence can be the main source of information for the general public, one that may or may not be saturated with bias - framing AI in either a positive or negative light. As such, we ask: how does media bias toward AI differ across business, political, and general interest news outlets in the United States? Understanding these biases becomes especially important as media literacy in the United States continues to be an essential focus in combating intentionally misleading or inaccurate information in the media (Boston University, 2024). Additionally, many media outlets function on the premise of manufactured consent (Pizarro, et. al., 2022) - framing and filtering information through five key pillars: ownership (corporate control of media), advertisement (catering to the interests of advertisers), sourcing (reliance on government or corporate spokespeople), flak (negative responses to dissenting media opinions), and fear ideology (focus on a common enemy, i.e. communism, terrorism, or other ideologies). For example, we expect to see more positive bias for AI from media outlets primarily focused on business or financial reporting, as it is in their best interest to frame AI positively to promote their corporate partners or advertisers, as well as to sensationalize the potential of AI while minimizing the potential negatives (exacerbating social biases, job loss, etc.) in favor of a larger enemy (profit loss, reduced market dominance, etc.). Another trend we expect to see is the defining of a common enemy for the general public through a focus on global threats (China, Russia, etc.) of AI in privacy concerns or market dominance (Ittefaq, et. al., 2025). Overall, this topic gives us an excellent framework for applying topics learned in class, with many interesting precedents in comparative research to investigate.

Section 0.b: Method

We explored various ideas for how to procure a dataset of media related text that we could use in this project to help us answer this question. We plan to use a publicly available API called NewsAPI (https://newsapi.org/docs/endpoints/top-headlines). Through the free version of this API we can access news headlines from various sources. We plan to utilize the key words and phrases parameter to identify the headlines that are related to our chosen topic of AI. There are some limitations with this data source as the free version only offers a limited number of AI requests daily, and a limited time frame only allows us to access news headlines from the past month. As such, this project will be looking at a snapshot of the current media coverage on AI. We are actively exploring pulling data from this API but welcome any suggestions of alternative data sources. Ideally our data would be a robust set of media headlines about AI from a spectrum of sources. We aim to use NLP for sentiment analysis to examine if the media coverage is generally positive or negative, and if this varies amongst sources. Additionally, we plan to use BERTopic to get a more detailed view into what specifically the media is writing about regarding AI, and what that looks like from one source to another.

Section 0.c: Hypothesis

Null Hypothesis, H0: There is no difference in AI-related media bias across business, political, and general-interest news outlets.

Alternative Hypothesis, H1: AI-related media bias differs across business, political, and general-interest news outlets.

Rationale: We expect business and financial news outlets to exhibit more positive bias toward AI, emphasizing its economic potential and downplaying social or ethical risks in ways that align with corporate interests and advertiser incentives. In contrast, general-interest outlets are expected to frame AI through narratives of global competition and national security threats, often identifying external actors such as China or Russia as common enemies. Political news outlets are expected to show more polarized coverage, amplifying either the risks or benefits of AI depending on ideological positioning. Overall, we hypothesize that each outlet type will employ distinct framing strategies that reflect their institutional goals and audience expectations.
