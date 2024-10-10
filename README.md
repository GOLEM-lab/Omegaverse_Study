# Data and Analysis of the Omegaverse Trope in Fanfiction

This repository contains data and analysis code related to the study titled "Exploring the Evolution of Gender Power Difference through the Omegaverse Trope on AO3 Fanfiction," authored by Xiaoyan Yang and Federico Pianzola. The study explores gender power dynamics within the Omegaverse trope, a fan-created narrative construct characterized by distinct secondary gender categories (Alpha, Beta, Omega), on the Archive of Our Own (AO3) platform.

## Goal of the Study
This research focuses on examining power relationships in Omegaverse slash fanfiction, spanning eight popular fandoms: Japanese anime, K-pop, Western TV series, and Western films. By employing connotation frames and the Riveter pipeline, we measure the gendered power dynamics in fanfiction, showing that Alphas tend to have higher power scores compared to Omegas. Our findings reveal significant variance across fandoms, with some indicating stronger within-group consensus as fanfiction writing becomes more prolific. This study sheds light on how fan communities negotiate and evolve traditional gender power structures.

## Repository Contents
### CHR2024-Gender Power Difference-code.ipynb
This Jupyter notebook contains the code used to calculate and visualize gender power dynamics within Omegaverse stories using the Riveter NLP toolkit (available at Riveter NLP). The analysis is part of our accepted short paper for the Computational Humanities Research 2024 (CHR2024) conference, which will be presented in poster format.

### CHR2024_Data.zip
This dataset includes metadata and power scores for the Omegaverse slash relationships analyzed in the study. Due to copyright restrictions, the actual content of the stories cannot be made publicly available, and all story IDs and author information have been anonymized.

Example dataset (e.g., AO_CD_DC_result.csv for Castiel/Dean in the Supernatural fandom) contains the following columns:

story_id: Unique identifier for the story;

relationships: Fanfiction relationship tags;

published: Date of publication;

genre: Story genre;

Castiel_power_score, Dean_power_score: Power scores computed using Riveter for key characters;

Alpha_power_score, Omega_power_score: Power scores for secondary genders;

Castiel_list, Dean_list, Alpha_list, Beta_list, Omega_list: Verbs that identified per persona by Riveter Sap's lexicon;

gender_power_difference: Calculated difference between Alpha and Omega power scores;

year: Year of publication;

additional_tags: Any additional tags associated with the story.

## Limitation and Future Works
Our current study is limited to English fanfiction within popular fandoms, which may include multiple stories written by the same authors. Additionally, we observed interactions between the original plots and the computed power dynamics in specific fandoms (e.g., Hannibal and Yuri on Ice). Future work will expand the corpus to include a greater variety of languages, plot types, and themes, while controlling for author uniqueness. We will also enhance the analysis with more granular linguistic features, such as adjectives and adverbs, and include tags like "Non-Traditional Alpha/Beta/Omega Dynamics" to explore their impact on gender dynamics.

## Citation
To cite this study:

Yang, X., & Pianzola, F. (2024, December). Exploring the evolution of gender power difference through the Omegaverse trope on AO3 fanfiction. In Proceedings of the Computational Humanities Research 2024.
