# AURA — Pop Culture Identity System

AURA asks for 3-5 of your favorite interests and generates a poem for you

I made AURA to learn about the different layers of AI operating systems, particularly how the personalization layer produces tailored responses. I used the free version of NVIDIA's Nemotron 3 Nano Omni model, and saw how limited the multimodal system is in understanding and create pop culture references. 

hoping to use my interests in pop culture to produce tailored responses for fans.  

AURA learns what fandoms you're interested in, made for the multifandom fan. You'll tell AURA what you're a fan of, whether that's focused on music, sports, celebrities, video games, or other pop culture interests and AURA then generates a personalized “daily vibe briefings.”

---

## Why I Built This

I wanted to explore a more emotional and identity-driven direction for AI personalization.

Most AI assistants focus on utility and productivity. AURA instead explores:

* cultural memory
* aesthetic modeling
* emotional personalization
* fandom-aware computing
* AI-native identity systems

The goal was not to build a productivity tool, but to prototype a more human and culturally-aware AI layer for future personal devices.



## Concept

AI can learn:

* our schedules
* notifications
* locations
* search history

But it rarely understands:

* why we connect with certain media
* emotional patterns across our interests
* recurring aesthetic preferences
* cultural identity

AURA explores what an AI personalization layer could look like if it modeled taste, fandom, and emotional affinity instead of just productivity.

---

## Features

### Cultural Identity Input

Users enter 3–5 things they love:

* artists
* sports teams
* games
* streamers
* films
* aesthetics
* internet culture
* celebrities
* fandoms

### AI-Generated Daily Briefings

AURA generates:

* emotional summaries
* aesthetic drift analysis
* media recommendations
* stream/watch/listening suggestions

### Persistent Memory

The app remembers user interests locally using browser storage and adapts future interactions.

### Early-2000s Inspired UI

The interface is intentionally styled like an early internet desktop experience:

* retro terminal aesthetics
* chunky borders
* bright UI colors
* nostalgic web-inspired layouts

---

## Tech Stack

* React
* Vite
* OpenRouter API
* Plain CSS
* localStorage memory persistence
* Vercel deployment

---

## Local Setup

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/aura-ai.git
cd aura-ai
```

Install dependencies:

```bash
npm install
```

Create a `.env` file in the root directory:

```env
VITE_OPENROUTER_API_KEY=your_openrouter_key
```

Run the development server:

```bash
npm run dev
```

---

## Example Prompt

Input:

* Arcane
* Mitski
* San Francisco Giants
* Jerma985
* Rosalía

Possible Output:

Today's energy:
Late-night emotional processing with competitive optimism.

You're drawn toward worlds that are:

* emotionally intense
* slightly chaotic
* deeply human
* performative but sincere

Current aesthetic drift:
baseball nostalgia + hyperpop melancholy + neon intimacy

Recommended:

* Watch: Moneyball
* Album: Desire, I Want To Turn Into You
* Stream vibe: Jerma baseball simulator chaos

---
