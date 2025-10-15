# Multi-Agent-Restaurant-Booking-Simulation
This project demonstrates a multi-agent communication system where restaurant and customer agents interact through structured performative messages using the OpenAI GPT API. Each agent maintains its own memory, internal state, and reasoning chain to negotiate restaurant bookings autonomously.

🧠 Overview
- Restaurant Agents: Manage booking availability, respond to proposals, and track occupancy.
- Customer Agents: Sequentially propose bookings, interpret accept/reject responses, and confirm reservations.
- Communication Protocol: Based on structured JSON messages (e.g., PROPOSE, ACCEPT_PROPOSAL, CONFIRM, INFORM).
- Concurrency: Uses Python’s threading to simulate multiple agents acting independently and simultaneously.

⚙️ Features
- Real-time multi-agent negotiation
- Dynamic agent memory and state tracking
- GPT-based decision-making and language grounding
- Threaded simulation of concurrent customer arrivals

🧩 Tech Stack
- Python
- OpenAI API (gpt-4o-mini)
- threading, json, time, random

📚 Concept:
This project explores Large Language Models as autonomous communication agents, showcasing how GPT can coordinate decisions between multiple reasoning entities in a simulated environment.
