# Co-Developing with Generative AI

Introduction to Command Line Agents

---

## Today's Tools

- Site Studio
- Terminal/PowerShell
- Gemini CLI

---

## Before We Start

**Using lab computers?**
- Sign in now

**Brought your own computer?**
- Make sure you can access your terminal/PowerShell

**Everyone:**
- We'll help you install required tools as we go

Need help? Just ask!

---

## Ice Breaker: Site Studio

[tools.cuny.qzz.io/site-studio/](https://tools.cuny.qzz.io/site-studio/)

**Powered by Claude Sonnet 4.5**

After the opening demo, share your ideas for follow-up prompts

---

## Understanding Large Language Models

What's happening under the hood?

---

### How Do LLMs Work for Coding?

LLMs are trained on billions of lines of code from open-source projects, documentation, and Stack Overflow

They predict what code should come next based on patterns

Can complete functions, suggest implementations, explain code, and debug errors

**Command-line agents** (like Gemini CLI) can execute commands, read/write files, and iterate on code

Different from chat interfaces - they actively interact with your development environment

---

### Limitations for Coding

- **Generates plausible but broken code** - Syntax may look right but logic can be flawed
- **Outdated libraries/syntax** - May suggest deprecated methods or old versions
- **Security vulnerabilities** - Can generate code with SQL injection, XSS, or other security issues
- **Can't understand your full codebase** - Limited context window means it doesn't see everything
- **You must verify and test** - Always review, understand, and test generated code

---

### Prompt Engineering Basics

How you ask matters as much as what you ask

**Be specific:** "Create a Python function that sorts a list of dictionaries by the 'date' key"

vs. "Help me sort some data"

**Provide context:** Share relevant code, error messages, project structure

**Iterate:** Refine your prompts based on results

---

## Command Line Basics

Let's get comfortable with the terminal

---

### What is the Terminal?

A **terminal** (or command line) is a text-based interface for controlling your computer

Instead of clicking buttons and icons, you type commands

Why use it?
- More powerful and precise control
- Essential for development work
- How AI coding agents interact with your system

---

### Opening Your Terminal

**Mac:**

1. Press `Cmd + Space`
2. Type "Terminal"
3. Press Return

**Windows:**

1. Press Windows key
2. Type "PowerShell"
3. Press Enter

---

### Essential Commands

| Command | Description |
|---------|-------------|
| `ls` | List files & folders in current directory |
| `mkdir <name>` | Create a new folder |
| `cd <name>` | Move into a specific folder |
| `pwd` | Show your current location |
| `cd ..` | Move up one level to parent directory |

---

## Installing Gemini CLI

---

### Windows (PowerShell)

1. Install Node.js: [nodejs.org/en/download](https://nodejs.org/en/download)
2. Install Gemini CLI:
   ```bash
   npm install -g @google/gemini-cli
   ```

---

### macOS (Terminal)

1. Install Homebrew: [brew.sh](https://brew.sh/)
2. Install Gemini CLI:
   ```bash
   brew install gemini-cli
   ```

---

### Login Setup

After installation, run `gemini` to authenticate with Google

Choose "Login with Google" and follow the browser prompt

Free tier: 60 requests/min, 1,000 requests/day

Having technical issues? Just ask!

---

## Critical Questions

Before we build, let's pause and reflect

---

### Ethical Challenges

**Academic Integrity**

How do we cite AI-assisted work? What's collaboration vs. skills offloading?

**Bias & Fairness**

AI models reflect biases in their training data

**Environmental Impact**

Training and running AI systems consume significant energy

---

### Power & Labor Considerations

**Who builds these systems?**

Often underpaid workers label data and moderate content

**Who controls AI?**

Major tech companies control development and access

**Privacy concerns**

What data are you sharing? How is it used for training?

---

### Why Use AI Coding Tools, then?

- Speeds up repetitive tasks (boilerplate code, file structure setup)
- Helps learn new languages/frameworks by example
- Debugging assistance and explaining error messages
- Documentation and code explanation
- Prototyping and exploring ideas quickly
- Reduces context switching (staying in terminal vs. searching Stack Overflow)
- Democratizes access to coding for people without CS backgrounds

---

### When NOT to Use AI

- When learning fundamentals for the first time
- For sensitive or confidential data/code
- When you need guaranteed accuracy (medical, legal, safety-critical)
- When the goal is to develop your own problem-solving skills
- When it would violate academic or professional policies

**Use AI as a tool, not a replacement for understanding**

---

## Choose Your Project Track

**Website**
Portfolio, link tree, small HTML/CSS/JS pages

**Visualization**
Simple map, chart, or interactive element

**Program/Script**
Basic Python task (text parsing, data cleanup, small utility)

---

## Start with a README

Ask the agent to create a README.md file first

This helps you understand and approve the workflow before building

The README should:

Describe your project idea

Outline the project structure

List key features or goals

---

## Hands-On Activity

After approving the README.md, work with the agent to implement the plan from your README

**Duration:** 15-20 minutes

We'll walk around the room to help

Choose your track and start building!

---

## Let's Reflect

What did we learn?

---

### Discussion: Your Experience

- **What worked well?** When did the AI agent help most?
- **What didn't work?** When did you get stuck or frustrated?
- **Surprises?** Did the AI do anything unexpected (good or bad)?
- **Trust & verification:** How did you know if the generated code was correct?

---

### Critical Assessment

Think about these questions:

When is AI-assisted coding **appropriate** for your work?

When might it be **inappropriate** or problematic?

How would you document/cite that you used AI in a project?

What skills do you still need to develop yourself?

---

## Resources

**[Claude Code](https://code.anthropic.com/)** - AI assistant for your entire development workflow

**[Google AI for Students](https://gemini.google/students/)** - 1-year free trial (requires SheerID verification)

**[GitHub Copilot](https://github.com/features/copilot)** - AI code suggestions in your editor

**[GitHub Desktop](https://desktop.github.com/)** - Visual Git interface, no command line needed

---

## Thank You!

Questions?

Happy building!
