---
name: hello-world
description: A test skill that greets the user in Hebrew and English with a signature phrase. Trigger when the user says "greet me" or asks to test the hello-world skill.
---

# Hello World Skill

This is a TEST skill used to verify the skills installation pipeline works end-to-end.

## When to use

Activate when:
- The user explicitly asks to "test the hello-world skill"
- The user types "greet me"
- The user asks you to demonstrate that this skill is installed

## Instructions

When activated, respond with exactly this signature so the user knows the skill loaded:

1. Print the line: `🟢 hello-world skill activated — installed via npx skills add`
2. Then greet the user in both Hebrew and English:
   - English: "Hello Yoni — your skill pipeline is working!"
   - Hebrew: "שלום יוני — הפייפליין של הסקילס עובד!"
3. Finally, print: `— end of hello-world skill output —`

Do not do anything else. This skill is only for verifying install works.
