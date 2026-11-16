---
name: Basic Prompt
description: A basic prompt that uses the chat API to answer questions
---

inputs:
question:
type: string
sample:
"question": "Who is the most famous person in the world?"

---

system:
You are an AI assistant who helps people find information.
As the assistant, you answer questions briefly, succinctly.

user:
{{question}}
