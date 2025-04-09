# SCVBench

## Overview

Despite advancements in Large Vision-Language Models (LVLMs), their ability to understand long-term story-level video content remains limited. Challenges arise from oversimplified temporal information handling and action/event-centric training data biases.

## Introducing SCVBench

SCVBench is a novel benchmark for story-centric video understanding. It evaluates LVLMs through an event ordering task, broken into sub-questions leading to a final question, quantitatively measuring temporal reasoning. The dataset includes 1,253 final questions and 6,027 sub-question pairs from 925 videos, forming continuous multi-turn dialogues.

Experiments show that while closed-source GPT-4o performs best, most open-source LVLMs struggle with story-level understanding. See `json` for detailed samples.

---

# StoryCoT

StoryCoT is a method designed to enhance story-centric video understanding. It excels in capturing nuanced temporal dynamics and high-level story evolution, addressing the limitations of existing LVLMs.

### Key Features

- Enhanced temporal reasoning for complex video narratives.
- Focus on story-level understanding beyond actions/events.
- Multi-turn dialogue integration for improved context modeling.

**We are evaluating the various VideoLLMs and StoryCoT based on lmms-eval, and the code will be released soon.**
