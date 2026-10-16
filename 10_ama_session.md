## 1. **What are the different types of Claude models?**  
   Claude models include Haiku (fast and efficient), Sonnet (balanced performance), and Opus (advanced reasoning and complex tasks).

## 2. **What are Skills?**  
   Skills are reusable instructions and resources that help Claude perform specific tasks consistently, such as coding, writing, or data analysis.

## 3. **Where do Skills live?**  
   Claude Code Skills are usually stored in `SKILL.md` files inside `.claude/skills/` folders, either in a project or in your personal configuration directory.

## 4. **What is a Stop hook?**  
   A Stop hook runs when Claude finishes responding or attempts to stop, allowing you to perform checks or run additional actions.

## 5. **What is a `PostToolUse` hook, and where is it used?**  
   A `PostToolUse` hook runs immediately after Claude uses a tool, helping automate tasks such as formatting code, running checks, or logging tool activity.

## 6. **Explain the agent loop.**  
   The agent loop is the process in which an AI receives a task, reasons, uses tools, observes the results, and repeats until the task is completed.

## 7. **Explain extended thinking.**  
   Extended thinking allows Claude to spend more effort reasoning through complex problems before answering, which can improve its performance on challenging tasks.