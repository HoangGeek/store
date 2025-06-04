+++
author = "HoangYell"
title = "All LLM Tools You Should Know"
date = "2022-05-19"
description = "A comprehensive guide to the most important LLM (Large Language Model) tools, including features, usage tips, and practical advice for developers."
draft = false
tags = ["AI"]
categories = [
    "Tech"
]
image = "https://i1.wp.com/miro.medium.com/v2/resize:fit:700/1*DJmqEqyrlNUwYvJjl8eoQw.png"
+++

## Github Copilot
- Established in 2021, GitHub Copilot is an AI-powered code completion tool developed by GitHub in collaboration with OpenAI.
- Used in code editors/IDEs like Visual Studio Code, JetBrains IDEs, and Neovim that help you write code faster and with fewer errors.
### How to Use
- Start coding as usual; Copilot will automatically suggest completions as you type. Accept a suggestion by pressing `Tab` or `Enter`.
- Right-click on code and select Copilot to see alternative suggestions.
- In the Chatbox:
  - Reference multiple files, classes, or headers by typing `#file`, `#class`, or `#header` for more targeted responses.
  - Paste images directly into the Chatbox for visual context.
  - Use the 'Add Context' button to provide additional information for more accurate answers.
  {{< video "https://github.blog/wp-content/uploads/2025/05/7628641195839613148mode-selector.mp4" >}}
- Enable some preview features that are not yet available in the main version of Copilot. To do this, go to `File > Reference > Settings` and enable the desired features.
![enable preview](https://i.postimg.cc/dsH2ZffB/Screenshot-From-2025-05-20-20-24-07.png)


#### 🟩 **Ask Mode: Your Instant Code Companion**
- **Think of it as:** Google for code — embedded in your editor
- **CRUD equivalent:** 🟢 **Read (R)**
- **Purpose:** Get answers about code, syntax, logic, libraries, or best practices.
- **How it works:** Highlight code or ask a question, and Copilot replies with explanations, examples, or suggestions. It never changes your code in this mode.
- **Best for:** Learning, debugging, exploring new APIs, or getting quick syntax help.
- **Mindset:** “Just tell me what this is before I touch anything.”

#### 🟨 **Edit Mode: Your On-Demand Code Editor**
- **Think of it as:** A smart junior dev who follows your exact orders
- **CRUD equivalent:** 🟢 **Read + 🟡 Update (RU)**
- **Purpose:** Modify code based on your instructions, only where you specify.
- **How it works:** Highlight code, give a natural language instruction (e.g., "add error handling"), and Copilot rewrites the selected part. It shows diffs before making changes and won’t touch anything else.
- **Best for:** Refactoring, repetitive code updates, enforcing code style, or safe improvements.
- **Mindset:** “I know what to do — just do it for me.”

#### 🟥 **Agent Mode: Your Autonomous Dev Assistant**
- **Think of it as:** A powerful engineer who takes your idea and runs with it
- **CRUD equivalent:** ✅ **Full CRUD (Create, Read, Update, Delete)**
- **Purpose:** Automate complex coding workflows from a single prompt.
- **How it works:** Give a high-level instruction and Copilot plans, edits, and executes across your project. It can create new files, modify many at once, run commands, and loop on tasks until complete. It only asks for permission if something is risky.
- **Best for:** Feature generation, scaffolding, project-wide updates, or complex automation.
- **Mindset:** “Here’s the vision — go build it, I’ll watch.”

{{< video "https://github.blog/wp-content/uploads/2025/05/sn0404-agent-dark.mp4" >}}

- Summary Table

| Mode      | Power Level          | CRUD Scope | Ideal For                                | Control Style                       |
| --------- | -------------------- | ---------- | ---------------------------------------- | ----------------------------------- |
| **Ask**   | 🟢 Light             | R          | Learning, exploring, debugging logic     | Fully manual                        |
| **Edit**  | 🟡 Medium            | R + U      | Refactoring, quick fixes, inline changes | Semi-automated (with review)        |
| **Agent** | 🔴 High (Autonomous) | CRUD       | Feature building, automation, workflows  | Mostly autonomous (with guardrails) |


## Gemini Code Assist
- Established on February 25, 2025, Same as Github Copilot Ask mode, sometime it can suggest a better solution than Copilot. Actually, I don't use it much because Github Copilot is the best for me.

## https://gemini.google.com/app
- Gemini is like ChatGPT but it have an interesting feature that is "Gem", 
- Precision Customization: "Gems" allow building specialized AI agents with bespoke instructions and knowledge bases – more than just custom prompts.

## https://notebooklm.google/

## https://manus.im/

