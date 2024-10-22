# Team RicAI 

<b>Team members:</b> Ricards Liskovskis

## Autonomous Agents Hackathon submission

### The idea

The idea was to develop an Autonomous AI Agent for software testing.

In simple words, delegating the time consuming and expensive software testing processes to an agent
The overall vision of such tool would be to:

1. Understand (complex) software requirements and business logic
2. Generate test cases
3. Work with unit tests, usability and acceptance tests (tools like Selenium, etc.)
4. Provide feedback and test reports

### Progress in hackathon

The following was implemented:

1. Code storage and retrieval tool: [github repo](https://github.com/AutoDevTestAgent/ricai_unittestgen_tool/tree/master)
2. Unit test generation tool: [github repo](https://github.com/AutoDevTestAgent/ricai_unittestgen_tool/tree/master)
3. Overall SuperAGI agent with integrates tools (mentioned above) + additional steps for report sending: [github repo](https://github.com/AutoDevTestAgent/ricai_superagi_instance/tree/main)

### Tech used

1. SuperAGI agent framework for the core
2. Weaviate vector database for code storage and retrieval
3. GPT-Engineer for unit test generation

### Other links

Presentation: [PDF slides](ricai_autonomous_agents.pdf)
<br> 
Video: [YouTube video](https://youtu.be/9mCSgtaFG1k)
<br>
Agent setup: [docx file](resources/agent%20setup%20document.docx)
