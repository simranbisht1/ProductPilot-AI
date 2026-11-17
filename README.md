# ProductPilot AI

### A Multi-Agent AI Product Management Assistant

ProductPilot AI is an AI-powered product management assistant built using the OpenAI Agents SDK.
It uses specialized agents to analyze customer feedback, research competitors, prioritize features,
generate PRDs, plan development sprints, and analyze product metrics.

The demonstration uses a fictional student productivity application called **StudyFlow**.

## Key Features
- Customer feedback analysis
- Competitor research
- Weighted feature prioritization
- Human-in-the-loop approval and revision
- Product Requirements Document generation
- Development sprint planning
- Product analytics and KPI recommendations

## AI Agents
| Agent | Responsibility |
|---|---|
| Feedback Analysis | Identifies customer problems and trends |
| Competitor Research | Examines competitor features and gaps |
| Feature Prioritization | Ranks features using weighted criteria |
| PRD Writer | Generates product requirement documents |
| Sprint Planner | Creates development tasks |
| Product Analytics | Analyzes metrics and recommends KPIs |

## Workflow
1. Analyze customer feedback.
2. Research competitor features.
3. Calculate feature priorities.
4. Obtain human approval.
5. Revise recommendations when requested.
6. Generate the approved feature's PRD.
7. Create a development sprint plan.
8. Analyze product metrics and recommend KPIs.

## Prioritization Weights
- Customer demand: 40%
- Competitor gap: 25%
- Business value: 20%
- Implementation ease: 15%

## Demonstration: StudyFlow
The approved feature in the final demonstration workflow is **Calendar**.

### Generated Reports
- [Calendar PRD](reports/calendar_prd.md)
- [Calendar Sprint Plan](reports/calendar_sprint_plan.md)
- [Calendar Analytics Report](reports/calendar_analytics_report.md)

The project uses synthetic demonstration datasets, not real production data.

## Technology Stack
- Python
- Google Colab
- OpenAI Agents SDK
- Pydantic
- Pandas
- Gemini 2.5 Flash Lite through an OpenAI-compatible endpoint

## Project Structure
```text
ProductPilot-AI/
├── ProductPilot_AI.ipynb
├── customer_feedback.csv
├── competitor_data.csv
├── engineering_estimates.csv
├── product_analytics.csv
├── README.md
└── reports/
    ├── calendar_prd.md
    ├── calendar_sprint_plan.md
    ├── calendar_analytics_report.md
    ├── revision_request.txt
    ├── structured_revision.json
    └── workflow_state.json
```

## Getting Started
1. Clone this repository.
2. Open ProductPilot_AI.ipynb in Google Colab.
3. Install the dependencies specified in the notebook.
4. Add your Gemini API key to Google Colab Secrets.
5. Run the notebook cells in order.

Never hardcode API keys or commit credentials to GitHub.

## Current Status and Limitations
- Six specialized agents have been developed.
- The human approval and revision workflow has been demonstrated.
- Calendar PRD, sprint plan, and analytics reports have been generated and saved.
- The latest fresh end-to-end workflow attempt was blocked by a Gemini API free-tier rate limit.
- This is a demonstration prototype using synthetic data, not a production deployment.

## Author
Developed as an AI Agents capstone project.