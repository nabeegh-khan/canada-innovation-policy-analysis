# Canada Innovation Policy Analysis: News and YouTube Collection and Policy Visuals

Course project for MIE1624H, Data Science and Analytics, University of Toronto, Winter 2025. Group of five.

The group acted as consultants recommending policies to raise Canada's standing in the Global Innovation Index (GII) 2024, with a report, a business pitch and a public-relations package. This repository holds my parts: two data-collection streams with their findings reports, and the project's visualisation deliverable.

*Code AI-assisted; design and analysis my own.*

## My parts

- **News collection (`notebooks/newsapi_collection.ipynb`).** Queried NewsAPI for innovation-policy coverage of Canada, the USA, China, Germany, the UK, Sweden and India, then scored sentiment with VADER and grouped articles by topic with TF-IDF and k-means.
- **YouTube collection (`notebooks/youtube_api_collection.ipynb`).** Searched the YouTube Data API for policy videos on the same countries and grouped them by topic with TF-IDF and k-means.
- **Findings reports (`reports/`).** One report per stream comparing Canada with leading countries on R&D spending, startup funding, AI policy, talent and industry-academic collaboration, ending in policy recommendations that fed the group's proposal.
- **Visualisations (`notebooks/policy_visualizations.ipynb`).** 14 matplotlib and seaborn figures for the report and pitch: Canada against top performers on GII factors, top 15 features by importance, a policy-to-factor matrix, a radar chart, the policy roadmap, projected GII score, annual and cumulative budget impact, comparative budget allocation and KPI growth targets.

- **Review, report and presentation.** Edited every section of the group report in review and did much of the presentation design.

Teammates' parts, not included here: GII PDF extraction and feature engineering, the Kaggle dataset analysis, Google Scholar collection, the policy proposal, the implementation steps and the chatbot demo.

## Notes

- The notebooks are the cleaned versions submitted for the course. API keys were removed and live API calls were commented out, so the collection notebooks do not run as-is. To rerun them, restore the calls and supply your own NewsAPI, YouTube Data API and OpenAI keys.
- The figures render inside the visualisation notebook on GitHub.
- The findings reports were converted from Word to Markdown.
