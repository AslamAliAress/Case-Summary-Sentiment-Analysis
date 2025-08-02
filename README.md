# Case-Summary-Sentiment-Analysis
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/00fba904-55e3-438b-8a76-91a34cbcc810" />

#2. Case Summary +  Sentiment Analysis
Objective:
 Equip agents with quick insights into case details and customer sentiment to improve service quality.
Key Capabilities:
●	Case Summary Generation:
○	Automatically summarize key case fields and activity history.
○	Trigger via Agentforce using the prompt:
“Can you summarize the case [caseID]?”
●	Sentiment Analysis:
○	Analyze the emotional tone of customer communications.
○	Trigger via Agentforce using the prompt:
“Can you do sentiment analysis of the case [caseID]?”

3 Ways to do this Case Summary 

1. Using Field Generation Prompt Builder
2. Onload using Screen Flow+ prompt template
3. Using Agent Icon Use The Prompt "Summarize the Case “CaseNumber” with Sentiment Analysis 


2. Case Summary + Sentiment Analysis +  Knowledge Article
Objective:
 Equip agents with quick insights into case details and customer sentiment to enhance service quality and improve customer interactions.
Key Capabilities:
●	Case Summary Generation:
 Automatically generate concise summaries of key case fields and the activity history.
 Trigger: Agents can invoke this feature via Agentforce by using the prompt:
 “Can you summarize the case [caseID]?”

●	Sentiment Analysis:
 Analyze the emotional tone of customer communications to gauge customer sentiment.
 Trigger: Agents can invoke this feature via Agentforce by using the prompt:
 “Can you do sentiment analysis of the case [caseID]?”

3 Ways to Generate Case Summary
1.	Using Field Generation Prompt Builder
 Leverage a configurable prompt builder to generate summaries based on selected case fields.

2.	Onload Using Screen Flow + Prompt Template
 Automatically generate and display case summaries and sentiment analysis when the case screen loads using Screen Flow combined with a predefined prompt template.

3.	Using Agent Icon with Prompt
 Agents can click the Agent Icon and use the prompt:
 “Summarize the Case [CaseNumber] with Sentiment Analysis”
 to quickly get insights on demand.

Additional Features to Include:
●	Knowledge Article Integration:
 Link or embed relevant knowledge articles for case solutions, enabling agents to access helpful information directly within the case view.

Case Management Flow
<img width="975" height="330" alt="image" src="https://github.com/user-attachments/assets/b65da7b7-51ff-4d9b-bff5-c09281293b25" />

Implementation 

*Note: For all Case Summaries, the following redirections:
●	The associated Knowledge Article should redirect to the corresponding record page.
●	The Case Owner and Contact names should be clickable and redirect to their respective record detail pages.


1.	Using Field Generation Prompt Builder
 Leverage a configurable prompt builder to generate summaries based on selected case fields.

<img width="981" height="262" alt="image" src="https://github.com/user-attachments/assets/5ea6a459-f19d-40a3-9bc4-a63ca86cd3cf" />
Einstein helps you fill out generative AI-enabled fields.

2.	Onload Using Screen Flow + Prompt Template
 Automatically generate and display case summaries and sentiment analysis when the case screen loads using Screen Flow combined with a predefined prompt template.
<img width="981" height="241" alt="image" src="https://github.com/user-attachments/assets/7a3d929b-30d1-41d3-a06d-c345c8bd534e" />

3. Using Agent Icon with Prompt

Over ride the Summarize case Standard Feature 
or
 Agents can click the Agent Icon and use the prompt: “Summarize the Case [CaseNumber] with Sentiment Analysis” to quickly get insights on demand.

<img width="981" height="456" alt="image" src="https://github.com/user-attachments/assets/7f6afe82-65f5-4636-87db-27f79d2a68da" />
<img width="981" height="464" alt="image" src="https://github.com/user-attachments/assets/05c00731-21d8-43fc-b3a9-cd07665d3308" />
