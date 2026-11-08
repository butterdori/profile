---
layout: post
title: "How National Nuclear Energy Plans Frame Small Modular Reactors"
date: 2026-08-05 08:00:00 -0400
description: "What 66 national energy policy documents reveal about the technical focus of national small modular reactor strategies and their limited discussion of broader urban energy needs."
tags: small-modular-reactors nuclear-energy energy-policy NLP urban-energy climate-resilience
categories: research
related_posts: false
---

*Daein Kang, John D Kim, Moe Kyaw Thu, and Brian Y An · Published in Environmental Research Letters, August 5, 2026*

Small modular reactors (SMRs) have attracted interest as a potential source of reliable, low-carbon electricity, with applications that could extend beyond power generation to district heating, industrial energy services, and local grid resilience. But **how are governments actually discussing SMRs in their national energy strategies**—as new reactor technologies, or as part of broader urban energy transitions?

In **“How national nuclear energy plans frame small modular reactors (SMRs): evidence from natural language processing of global policy documents,”** we examine the policy language surrounding SMRs across **66 national and international energy plans from eight countries**. We extract passages around SMR-related terms, yielding **more than 800,000 words**, and combine natural language processing—TF-IDF and topic modeling (LDA)—with qualitative close reading to understand which themes dominate and which receive less attention.

<figure style="margin: 1.5rem auto;">
  <img src="{{ '/assets/260805_smr_policy_framing/figure3_recreated.png' | relative_url }}" alt="Research roadmap from country and document selection through SMR-passage extraction and preprocessing, TF-IDF and LDA analyses, and robustness checks." style="display: block; width: 70%; height: auto;" loading="lazy">
  <figcaption style="font-size: 0.875rem; color: #666; margin-top: 0.4rem;">Research objectives and roadmap. Recreated from Figure 3 of the article.</figcaption>
</figure>

## Main findings

- **National SMR policy discourse is primarily technical.** Across countries, the most prominent terms emphasize reactor design, development, technology, projects, fuel, and safety. Both TF-IDF and topic modeling reveal this emphasis.
- **Urban and socioeconomic applications receive less attention.** Themes such as urban–rural equity, energy portfolio diversification, cogeneration, and climate resilience appear less prominently in the SMR-related policy text than the technical and regulatory vocabulary.
- **Less frequent does not mean absent.** Qualitative close reading reveals references to low-carbon goals, community benefits, hybrid energy systems, and local economic opportunities—notably in Canadian, British, and Japanese policy documents, even when these themes are less visible in keyword rankings.
- However, **the findings concern policy framing, not actual deployment.** Word-frequency rankings identify lexical prominence, not the significance of particular commitments or the reasons governments emphasize specific technologies.

<figure style="margin: 1.5rem auto;">
  <img src="{{ '/assets/260805_smr_policy_framing/table2_normalized_tfidf.png' | relative_url }}" alt="Top 15 country-normalized TF-IDF scores from Table 2, led by reactor at 1.00, development at 0.73, technology at 0.71, project at 0.60, and design at 0.57." style="display: block; width: 70%; height: auto;" loading="lazy">
  <figcaption style="font-size: 0.875rem; color: #666; margin-top: 0.4rem;">The 15 most salient terms in the policy corpus. Scores are relative, country-normalized TF-IDF values.</figcaption>
</figure>

## Study context

Our analysis begins with published energy plans and policy statements issued by national ministries and relevant agencies in the **United States, Russia, France, Japan, China, the United Kingdom, South Korea, and Canada**. The selected documents cover 2016–2025 and include both English-language documents and translated material. We apply NLP to extracted SMR-relevant text rather than treating all words in a national energy plan as SMR discourse.

<figure style="margin: 1.5rem auto;">
  <img src="{{ '/assets/260805_smr_policy_framing/figure4_document_selection_original.png' | relative_url }}" alt="Original Figure 4 showing how national energy ministries and subordinate agencies provide energy policy documents from which SMR keyword passages are extracted." style="display: block; width: 70%; height: auto;" loading="lazy">
  <figcaption style="font-size: 0.875rem; color: #666; margin-top: 0.4rem;">Selection of national policy documents and SMR-related passages.</figcaption>
</figure>

**The way governments frame an emerging technology affects which questions receive attention.** A national conversation focused primarily on reactor design and regulatory readiness may leave less room for the broader role of SMRs in urban energy systems, including resilience, community participation, equitable benefit-sharing, and integration with other energy sources. Our findings highlight these gaps in the policy discourse of SMRs with regards to energy transition.

[Environmental Research Letters — open-access article](https://doi.org/10.1088/1748-9326/ae8e92).
