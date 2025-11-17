Problem Statement
People often experience emotions like sadness, fear, anger, or powerlessness but lack a supportive framework that acknowledges their feelings, offers cultural grounding, and provides small, actionable steps.
Modern emotional AI tools feel generic, clinical, or impersonal.
At the same time, India’s spiritual traditions offer deep emotional frameworks through stories, Sanskrit wisdom, and reflective practices — but these teachings are rarely integrated with personalized digital systems.

This project explores how a culturally aligned emotional companion can give people gentle insight, reframing, and mindful micro-actions when they feel overwhelmed.

Why Agents?
Emotions are multi-layered. No single model can detect emotion, recall patterns, reframe compassionately, tell mythic stories, provide wisdom, and recommend daily practices all at once — each task needs its own specialized reasoning style.

### Agents allow:

Separation of roles (emotion sensing vs. reframing vs. mythology vs. reflection).

Modular reasoning steps that pass context forward like a conversation.

Human-like flow where each agent enriches the user’s emotional journey.

A flexible pipeline that can grow and be improved agent-by-agent.

The multi-agent approach mirrors how humans process emotions: sense → reflect → contextualize → find meaning → act.

## What I Created (Architecture Overview)

I built a 5-agent spiritual emotional system where each agent performs a distinct function, passing its output to the next:

EmotionSenseAgent — Interprets emotional tone and cognitive bias.

MemoryAgent — Recalls emotionally similar moments from the current session.

ReframerCompanionAgent — Offers a warm, empathetic reframe.

MythicMotivationAgent — Creates an Indian epic–inspired story reflecting the user’s struggle.

WisdomAgent — Generates a Sanskrit-style verse with meaning and reflection.

DailyTrackerAgent — Suggests a small 5-minute activity to reinforce emotional grounding.

All agents combine into a single, flowing emotional-support response — culturally grounded but technically modular.

## Demo (What It Does)

When a user writes something like:

“I feel stuck and powerless…”

The system responds with:

Detected emotion & tone

Gentle reframe

A mythic-style story the user can see themselves in

A Sanskrit-inspired verse with reflection

A micro-activity to do right now

A stitched final message that feels human, warm, and spiritually grounded

Everything runs locally in Kaggle, producing a final readable text output and an exportable file.

## The Build (Tools & Implementation)

Designed a prompt-based multi-agent pipeline to simulate LLM behavior without external API calls.

Implemented each agent as a small rule-driven prompt transformer.

Built a local agent orchestrator to run emotion → reframe → story → wisdom → action steps.

Ensured the entire system works offline using Python only (Kaggle-safe).

Saved outputs as readable files for demonstration and evaluation.

Architecture:
User Input → Emotion Agent → Memory Agent → Reframer → Mythic Story → Wisdom → Micro-Activity → Final Combined Response

If I Had More Time:
Add real LLM-powered reasoning using Google ADK once async/context issues are resolved.

Expand mythic story generation with exact Mahabharata/Ramayana citations.

Build a memory database for long-term emotional patterns.

Add voice input + spiritual tone detection.

Develop a small web UI where users can chat with the spiritual companion.

Personalize guidance based on the user’s tradition (Bhakti, Yoga, Vedanta, Buddhist influences, etc.).


Link-> https://www.kaggle.com/competitions/agents-intensive-capstone-project/writeups/igita-an-indian-spiritual-multi-agent-emotion
