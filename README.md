
# Shamrock-Syntax
# This project is on pause, and it's unknown when I will start working on it
Project Idea: StudyLobby - Smart Collaborative Study Platform with an LLM Sidekick 🚀 One-Sentence Pitch StudyLobby makes a live, game-like study party out of boring cramming where friends do the quizzing with real notes, while an AI keeps making flashcards, quizzes, and cheat-sheets that are exactly for the part that is now the weakest.


⚙️ How It Works 

Upload Notes
The host drops & drags lecture notes (PDF).
Create a Lobby
Firstly, the host gets a magic link which he/she shares with classmates. Then, everyone joins in with 2 clicks.
LLM Magic (runs in <30 s)

Flashcards automatically generated (Q on front, answer + explanation on back)
Every piece is tagged: definition / formula / proof / example
Predicts the 20 hardest quiz questions

Live Study Round
Cards are passed to each player in turn. Player taps:
✅ Got it → card is sent to the quiz pool
❌ Nope → card returns later (spaced repetition)
Adaptive Quiz
3-minute blitz quiz auto-built from the “Got it” pile.
LLM instantly scores & finds weak spots.
Personal Study Pack (PDF in 10 s)
One-click download option:

“Your 3 weakest topics” with 1-paragraph refreshers
5 new analogies you will really remember
Printable micro-cheat-sheet + Anki export

🧠 LLM Superpowers

Turns 50 pages into 80 perfect flashcards
Explains wrong answers in your friend’s voice style
Scales difficulty per player (med-student vs. high-schooler)
Writes mnemonic songs on demand
💥 Why It’s Different

Multiplayer: Jackbox-like feeling, Anki-like working
Zero setup: no manual card typing
Proof-of-progress: PDF report you can send your prof
Free tier works for 1 lobby; paid = unlimited + voice explanations

🔧 High-Level Optimisation Blueprint (so you can ship v1 in 2 months)
Shift-Left Processing
Pre-compute embeddings + flashcards the second notes land. Cache forever.
Model Diet
4-bit AWQ on consumer GPU = 35 tokens/s on RTX 4060 
