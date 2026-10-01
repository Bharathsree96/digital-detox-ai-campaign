# digital-detox-ai-campaign
AI-powered social impact campaign — E.M.P.A.T.H framework, visual storytelling, n8n automation


# Digital Detox Week — AI-Powered Social Impact Campaign 🤖

## What is this project?
A complete AI-powered social impact campaign system for a 
Digital Detox awareness initiative targeting college students 
and young professionals (18–30) with heavy social media usage.

The project covers three components:
1. Ethical prompt engineering using a custom framework
2. AI-generated 6-scene visual narrative
3. Automated audience engagement workflow using n8n

---

## Problem it solves
Social impact campaigns often rely on generic, one-size-fits-all 
messaging that can feel preachy, manipulative, or disconnected 
from the audience's real experience. This project tackles that 
by building an ethical AI prompting framework that generates 
psychologically responsible messaging — and then automates 
personalised outreach based on each respondent's screen time behaviour.

---

## Tools Used
| Tool | Purpose |
|---|---|
| ChatGPT (GPT-5.3) | Prompt chaining for behavioural research & messaging |
| Claude | Visual narrative prompt generation |
| Gemini | Scene image generation and refinement |
| n8n | Automation workflow (Webhook → Sheets → Gmail) |
| Google Sheets | Respondent data storage and tracking |
| Gmail API | Personalised automated email delivery |
| Postman | Webhook testing and API validation |

---

## Task 1 — E.M.P.A.T.H. Prompt Framework

A custom 5-pillar prompting methodology designed to ensure 
AI-generated campaign content is ethical and psychologically responsible:

| Pillar | Description |
|---|---|
| E — Establish Context | Ground messaging in digital attention economy realities |
| M — Model Empathy | Write as if addressing one specific individual |
| P — Provide Ethical Guardrails | No shame, no fear, no manipulation |
| A — Adjust Emotional Escalation | Recognition → Understanding → Possibility → Invitation |
| T — Transform to Structured Output | Headline, script, awareness statements, CTA |
| H — Humanise the CTA | Gentle invitation, not a directive |

**Prompt chain used (5 prompts):**
1. Behavioural patterns of screen addiction
2. Emotional consequences of those patterns
3. Psychological triggers keeping users stuck
4. Guilt vs habit internal conflict
5. Motivational levers for voluntary change

**3 refinement iterations** produced the final campaign output.

---

## Task 2 — 6-Scene AI Visual Narrative

| Scene | Theme | Colour Palette |
|---|---|---|
| 1 | Overstimulation (night scrolling) | Cold blue, desaturated |
| 2 | Emotional fatigue (café, blank stare) | Muted grey-warm |
| 3 | Realisation (screen time report) | Warm natural light |
| 4 | Life beyond screen (park, golden hour) | Rich warm golden |
| 5 | Positive transformation (dinner, phones down) | Warm amber |
| 6 | Call to action (flat-lay, journal, tea) | Cream and terracotta |

Each scene went through prompt refinement to prevent 
over-dramatisation — removing theatrical elements like 
rain, loud laughter, and dramatic poses.

---

## Task 3 — n8n Automation Workflow

**Flow:**


Webhook (form submission)
→ Extract fields (Name, Age Group, Screen Time, Participation)
→ Conditional logic:
Screen Time ≥ 8 hrs → High Risk email
Screen Time 4–8 hrs → Moderate email
Screen Time < 4 hrs → Low Usage email
→ Prepare categorised data
→ Append to Google Sheets (with Category + Email Status columns)


**3 personalised email sequences:**
- 🔴 High Risk — empathetic outreach, digital detox invitation
- 🟡 Moderate — practical tips, screen limit suggestions
- 🟢 Low Usage — community supporter invitation

---

## Key Results
- ✅ Custom prompt framework with 5 pillars and ethical guardrails
- ✅ Campaign messaging refined across 3 iterations
- ✅ 6-scene visual narrative with controlled tone and 
  colour progression
- ✅ Fully functional n8n workflow with conditional 
  branching and automated Gmail delivery
- ✅ Google Sheets auto-updated with respondent 
  category and email status

---

## Project Structure

├── AI_Programme_Final_Project.docx ← Full project documentation
├── n8n_workflow.json ← Importable n8n workflow
├── campaign_visuals/ ← 6 scene images
│ ├── scene1_overstimulation.png
│ ├── scene2_emotional_fatigue.png
│ ├── scene3_realisation.png
│ ├── scene4_life_beyond_screen.png
│ ├── scene5_transformation.png
│ └── scene6_call_to_action.png
└── README.md


---

*Final Project — SkilloVilla Certified AI Generalist Programme (Mar 2026)*
