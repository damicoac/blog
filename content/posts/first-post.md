+++
date = '2026-03-31T13:52:37-04:00'
draft = false
title = 'This was written by a human'
+++

## abstract

I have been living at the intersection of machine learning and cyber security for awhile now. I am going to start sharing what the cutting edge looks like in that field. With all of the snake oil in AI/cyber, it is exhausting to vet any information you consume. The internet gives the impression that we are further behind in the field than we really are. Behind closed doors, we are out over our skis. Let me open that door a bit.


Here is a little something I have been working on. It is the basis of an agentic penetration tester. I implemented it as a MCP server so it works with any cli/model you want to use. The agent runs the tools and recommends follow-on tools to run. The MCP server provides the tools available, keeps the agent focused on the task and hand, and runs sub agents when neccessary. In this one minute demo, you can see the agent:
- decided to write a python script to extract a cookie from an auth session
- then using the tools/decision tree provided by the MCP server, begins testing the web app for XSS bugs.

This isn't a bunch of python scripts brute forcing the problem. After every step, the agent decides what is the best technique to try next.

[agentic pentester](https://drive.google.com/file/d/1RzlBMAB_ugwMRUxZ0Dltf45Hl23-PeBM/view?usp=share_link)




