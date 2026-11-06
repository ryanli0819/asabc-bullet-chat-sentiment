# 💬 ASABC: an LLM arbitrator for bullet-chat sentiment

**Published · IEEE AIxHeart 2024** · Grade 11 · Summer 2024

A few-shot prompt-tuning framework that turns a pre-trained LLM into a filter for negative "bullet chat" messages, the comments that fly across live streams on Douyu. Trained on just one hour of chat from a single gaming room, it held about 80% accuracy on 185k+ messages from other rooms, other games and even food and shopping streams.

## Demo video
[▶ Watch the demo](demo/asabc-explainer.mp4): a 15-second explainer animation of how the project works (not real project footage).

Also on my website: https://ryanli0819.github.io/#project-asabc

## What I did
- Came out of a summer research program with Purdue Prof. Yang's PhD team (30 hrs/week for 9 weeks).
- Bullet chat is hard: tiny messages full of memes and in-jokes ("666", "2333", "FGNB"), sarcasm and emojis like 🤡.
- Prompt-tuned the LLM instead of fine-tuning all of it, and used an iterative human-feedback loop to clean up rough keyword labels.
- Tested generalization on four much larger validation sets: same room later, other rooms, other games, and non-gaming streams.

## Skills used
- LLMs
- Few-shot prompt tuning
- Sentiment analysis
- Python
- Evaluation

## Results
- **~80%** accuracy
- **0.90** best F1
- **185k+** msgs tested

## Paper
Liu, X.; Jin, N.; Li, R.; Li, K.; Wang, M. Y.; Yang, B. "ASABC: An LLM-based Arbitrator for Sentiment Analysis in Bullet Chat Messages." IEEE AIxHeart, 2024.

## Code
The research code lives in the research team's repository: **https://gitlab.com/tonyyang1995/douyu**. It isn't copied here because it belongs to the whole group.

---
Made by **Ryan Li** · Data Analytics @ Purdue · [Portfolio](https://ryanli0819.github.io) · [GitHub](https://github.com/ryanli0819)
