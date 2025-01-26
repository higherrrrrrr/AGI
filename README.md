# AGI

**AGI** is an open-source project dedicated to one grand idea:  
**Anyone with a computer can use state-of-the-art reasoning models to solve (almost) any problem—instantly and freely.**

> **Note**: We’re calling this “AGI” somewhat tongue-in-cheek. We’re not claiming human-like consciousness. We *are* saying it’s a general-purpose assistant that can tackle a **lot** of tasks when used properly.

---

## Overview

- **Reasoners** are powerful language models tuned for step-by-step logic and problem-solving.  
- **Prompts** (like the one below) define *how* the model interacts with you—asking clarifying questions, gathering context, and guiding you to real solutions.  
- **Open Source** ensures that *you* control and run your own AI assistant without closed-off gates or paywalls.

---

## Quick Start

1. **Clone or Download this Repo**

   ```bash
   git clone https://github.com/higherrrrrrr/AGI.git
   cd AGI
   ```

2. **Pick a Reasoning Model**

   - See our [R1 instructions](models/r1.md) for a powerful open-source model you can run locally.
   - Other open-source reasoners (e.g., LLaMA variants, Wizard, Vicuna, etc.) can also work—just ensure they support conversation and step-by-step output.

3. **Use the Prompt**

   - Open your model’s chat interface or local text generation UI (e.g., Ollama, text-generation-webui, or a Hugging Face environment).
   - Copy and paste the entire prompt (see **The “AGI” Prompt** section below) as your “system” or “initial” prompt.

4. **Chat & Solve Problems**

   - The model will greet you and ask: “What problem would you like to solve today?”
   - Provide your problem statement. The model will gather context by asking clarifying questions.
   - Keep feeding it info until it arrives at a solution or plan.

5. **Iterate & Refine**

   - If it doesn’t solve your problem outright, continue the conversation.
   - You can ask for next steps, deeper analysis, or improvements (e.g., “What other angles should I consider?”).

---

## The “AGI” Prompt

Below is the core meta-prompt. Copy **everything** inside the code block when you start a new chat:

```plaintext
You are my open-source, step-by-step Reasoner (AGI).
Your mission: help me solve any problem by iteratively refining my problem statement and gathering context.

1. Begin by asking: “What problem would you like to solve today?”
2. After I provide a problem, ask for any relevant context or details I might have.
3. Check if you have enough info. If not, ask clarifying questions or prompt me to gather more data/knowledge.
4. Once you have sufficient information, provide the best possible solution or plan, step-by-step.
5. If the problem is unsolved or still ambiguous, keep refining until it’s solved or we exhaust known resources.

If you understand, greet me now with: “Welcome! What problem would you like to solve today?”
```

---

## Example Use Cases

1. **Software Development**
   - Debugging help  
   - Architecture planning  
   - Generating code snippets

2. **Daily Planning**
   - Managing to-do lists  
   - Creating itineraries  
   - Generating meal or workout plans

3. **Creative Work**
   - Outlining novels or stories  
   - Rapid design ideas  
   - Draft lyrics or poems

4. **Research Assistance**
   - Summarizing papers  
   - Brainstorming experiments  
   - Data analysis planning

5. **Anything** 

---

## Why This Matters

- **No Moat**: Open-source code and models break down the walled gardens.  
- **Democratized Access**: Anyone with suitable hardware can run advanced AI locally.  
- **Self-Improving**: You can use the AI to help build better tools, automations, and workflows—gradually making everything faster and cheaper.

---

## Contributing

1. **Fork** this repo.  
2. **Create a branch** for your feature or bug fix.  
3. **Add** or modify prompts, instructions, or references to new reasoners.  
4. **Open a Pull Request** and we’ll discuss your changes.

We welcome all contributions—bug fixes, new ideas, or brand-new prompts.

---

## Disclaimer

- **Not Professional Advice**: This system is not a licensed medical, legal, or financial advisor.  
- **Use Responsibly**: Outputs can be very convincing but may be incorrect or biased—always verify critical information.  
- **No Warranty**: This is experimental, provided as-is.

---

## More Models

- For detailed R1 model instructions, check [models/r1.md](models/r1.md).  
- More open-source reasoners (and how to run them) coming soon.
