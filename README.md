# Health Food Agent

A multi-agent AI system built with Google ADK and Gemini 2.5 Flash.

## Agents
- **health_root_agent** — orchestrator that routes to sub-agents
- **calorie_agent** — fetches nutrition data via Open Food Facts API
- **recipe_agent** — fetches recipe ideas via TheMealDB API
- **step_agent** — tracks daily step count

## Setup

1. Clone the repo
git clone https://github.com/MananSuthar07/Health-Agent.git
cd Health-Agent

2. Create and activate a virtual environment
python -m venv venv
source .venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Create a `.env` file inside `health_food_agent/`
GOOGLE_API_KEY=your_key_here

5. Run the app
adk web

## Try it

- "How many calories are in chicken?"
- "What can I cook with eggs?"
- "I walked 8000 steps and have salmon — what should I cook?"