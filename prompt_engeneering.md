### 🧠 **Quiz: Purpose of Prompt Engineering**

**Question:1**
What is the primary purpose of prompt engineering?

A) To design websites for AI tools\
B) To craft effective instructions that guide AI models toward desired outputs\
C) To build AI hardware systems\
D) To improve internet communication speed


**✅ **Correct Answer:**
**B) To craft effective instructions that guide AI models toward desired outputs**

---

**Question:2**

What is the primary difference between prompt engineering and context engineering when working with AI models?

A) Prompt engineering involves curating the information the model can access, while context engineering involves crafting the instructions given to the model.\  
B) Prompt engineering focuses on designing the model's architecture, while context engineering focuses on training the model with specific datasets.\  
C) Prompt engineering is about crafting the instructions given to the model, while context engineering involves curating the information the model can see when following those instructions.\  
D) Prompt engineering and context engineering are the same process, both involving the creation of training data for the model.

**Correct Answer:** C) **Prompt engineering is about crafting the instructions given to the model, while context engineering involves curating the information the model can see when following those instructions.**

--- 

**Question:3**

What is the primary goal of prompt engineering when working with AI models?

A) To design the model's architecture for better performance\
B) To tell the model how to behave and what to produce\
C) To curate the dataset used for training the model\
D) To optimize the model's hardware requirements

**Correct Answer:** B) **To tell the model how to behave and what to produce**

---

**Question:4**
What is the primary goal of context engineering when working with AI models?

A) To craft precise instructions for the model to follow\
B) To give the model the facts or examples it should rely on\
C) To design the model's training algorithm\
D) To optimize the model's output format

**Correct Answer:** B) **To give the model the facts or examples it should rely on**

---

**Question:4**
Which of the following is a primary lever of context engineering when working with AI models?

A) Defining the output schema for the model's response\
B) Providing few-shot examples to guide the model's behavior\
C) Using retrieval-augmented generation (RAG) to supply relevant documents\
D) Specifying the tone and style of the model's response

**Correct Answer:** C) **Using retrieval-augmented generation (RAG) to supply relevant documents**

---

**Question:5**
Which of the following is a key lever of prompt engineering when designing interactions with an AI model?

A) Selecting relevant documents for the model to reference\
B) Crafting the wording, structure, and constraints of the instruction\
C) Configuring the model's knowledge base for retrieval-augmented generation (RAG)\
D) Managing the model's memory across multiple turns

**Correct Answer:** B) **Crafting the wording, structure, and constraints of the instruction**

---

**Question:6**
What is the primary purpose of a prompt like “Be concise. Return valid JSON with fields X/Y/Z” in prompt engineering?

A) To provide the model with external documents for reference\
B) To specify the structure and format of the model's output\
C) To attach a company glossary or policy PDF for context\
D) To manage the model's memory across multiple interactions

**Correct Answer:** B) **To specify the structure and format of the model's output**

---

**Question:7**
What is the main goal of a request like “Attach the company glossary, latest policy PDF, and retrieved passages for this query” in context engineering?

A) To instruct the model on how to format its response\
B) To provide relevant information and resources for the model to reference\
C) To define the tone and style of the model's output\
D) To configure the model's internal architecture

**Correct Answer:** B) **To provide relevant information and resources for the model to reference**

---

**Question:8**
What should you avoid doing when crafting instructions for an AI model in prompt engineering to prevent undesirable outcomes?

A) Providing missing/irrelevant info that leads to hallucinations/outdated answers\
B) Using vague instructions that lead to messy/incorrect format\
C) Specifying clear roles and constraints for consistent output\
D) Including few-shot examples to guide the model\
E) Structuring the prompt to define the desired output schema

**Correct Answer:** B) **Vague instructions → messy/incorrect format**

---

**Question:9**
What should you avoid doing when curating information for an AI model in context engineering to prevent undesirable outcomes?

A) Using vague instructions that lead to messy/incorrect format\
B) Providing missing/irrelevant info that leads to hallucinations/outdated answers\
C) Using retrieval-augmented generation (RAG) to supply relevant documents\
D) Including up-to-date knowledge bases for accurate responsesv
E) Maintaining memory or state across multiple turns

**Correct Answer:** B)**Missing/irrelevant info → hallucinations/outdated answers**

---

**Question:10**
What should you do to effectively combine prompt engineering and context engineering when interacting with an AI model?

A) Use vague instructions and provide missing/irrelevant info to test the model's creativity \
B) Start with a good prompt and ground it with relevant context\
C) Provide a detailed prompt but omit any context to let the model rely on its internal knowledge\
D) Supply extensive context without specifying a clear task or output format\
E) Use only tool results without defining constraints or an output schema

**Correct Answer:** B) **Start with a good prompt and ground it with relevant context**

---

**Question:11**
Why are both prompt engineering and context engineering typically necessary for effective AI model interactions?

A) Prompt engineering supplies knowledge, while context engineering guides behavior\
B) Prompt engineering guides behavior, while context engineering supplies knowledge\
C) Both prompt and context engineering train the model's architecture\
D) Prompt engineering retrieves data, while context engineering formats output

**Correct Answer**: B) **Prompt engineering guides behavior, while context engineering supplies knowledge**


---

**Question:12**  
What is a key principle of effective prompt engineering, and how does it apply to defining output schemas?  

A) Keep prompts vague to allow flexibility, and avoid defining output schemas to encourage creativity  
B) Keep prompts short, specific, and testable, and define clear output schemas to ensure consistent results  
C) Use lengthy prompts with multiple examples, and rely on context to define output schemas  
D) Keep prompts short but generic, and use external tools to define output schemas  

**Correct Answer:** B) **Keep prompts short, specific, and testable, and define clear output schemas to ensure consistent results ** 

---




**Question:13**  
What is the core function of Large Language Models (LLMs) when generating responses?  

A) They understand text input in a human-like way and generate responses based on reasoning  
B) They take text input, predict the next most likely word/token, and continue to generate complete responses  
C) They retrieve pre-written responses from a database based on the input prompt  
D) They translate the prompt into a different language before generating a response  
E) They rely solely on external knowledge bases to produce accurate outputs  

**Correct Answer:** B) **They take text input, predict the next most likely word/token, and continue to generate complete responses**  

---


**Question:14**  
How do Large Language Models (LLMs) primarily operate, and what role does the prompt play in this process?  

A) LLMs understand prompts like humans and use the prompt to retrieve stored answers  
B) LLMs act as sophisticated autocomplete systems, using the prompt to set up the context for predicting the next word/token  
C) LLMs generate random responses and use the prompt to filter incorrect outputs  
D) LLMs rely on external APIs to process the prompt and generate responses  


**Correct Answer:** B) **LLMs act as sophisticated autocomplete systems, using the prompt to set up the context for predicting the next word/token**

---

**Question:15**  
What are the best practices for combining prompt engineering and context engineering to build reliable and scalable LLM applications?  

A) Use few-shot examples in all prompts and avoid retrieval optimization, ignoring citations for simplicity  
B) Prefer few-shot examples only when they generalize, optimize context retrieval with chunking, ranking, deduping, and logging, add citations and “answer only from context” instructions when correctness matters, and evaluate prompt and context layers separately  
C) Include all few-shot examples in retrieval and use vague prompts without output schemas to maximize flexibility  
D) Skip logging retrieved context and combine prompt and context evaluation into a single test  
 

**Correct Answer:** B) **Prefer few-shot examples only when they generalize, optimize context retrieval with chunking, ranking, deduping, and logging, add citations and “answer only from context” instructions when correctness matters, and evaluate prompt and context layers separately**


---

**Question:16**  
What is the best use of a temperature setting of 0.9 in a model for poetry?  

A) Solving math problems with precise answers  
B) Generating factual, data-driven responses  
C) Creating imaginative, experimental poems  
D) Producing repetitive, predictable text  

**Answer:** C) **Creating imaginative, experimental poems**  

---

**Question:17**  
What type of output is most likely when a model is set to a temperature of 0?  
A) Creative writing and brainstorming  
B) Math problems and factual answers  
C) Poetry and experimental content  
D) Random and unpredictable responses  

**Answer:** B) **Math problems and factual answers  **

---

**Question:18**
What does setting a higher token limit for a response affect?

A) Response accuracy  
B) Computational cost  
C) Response language  
D) User interface design  

**Correct Answer**: B) **Computational cost**

---

**Question:19**
What is the primary purpose of controlling the output length/token limits?

A) To improve response speed  
B) To manage computational resources  
C) To change the response tone  
D) To limit user access  

**Correct Answer**: B) **To manage computational resources**

---

**Question:20**
What happens if token limits are set too low for a task?

A) The response may be incomplete  
B) The computational cost increases  
C) The response becomes more accurate  
D) The system crashes automatically  

**Correct Answer**: A) **The response may be incomplete**

---

**Question:21**
Who should set the token limits appropriately according to the text?

A) The system administrator  
B) The user or system designer  
C) The AI model itself  
D) The network provider  

**Correct Answer**: B) **The user or system designer**


I understand you want the quiz in English, based on the previous context and the provided text about Top-K, Top-P, and temperature. Below is a revised quiz with three multiple-choice questions in English, using the exact questions and answers you specified, translated from Hindi to English, and formatted in plain text.

---
**Question:22**
Why do we use Top-K?

A) To increase response length  
B) To limit choices to top K most likely tokens  
C) To reduce computational speed  
D) To change the response language  

**Correct Answer**: B) **To limit choices to top K most likely tokens**  

---
**Question:23**
Why do we use Top-P?

A) To select tokens based on response length  
B) To limit choices based on cumulative probability  
C) To make responses less random  
D) To set a fixed number of tokens  

**Correct Answer**: B) **To limit choices based on cumulative probability**  

---
**Question:24**
What do Top-K and Top-P do when combined with temperature?

A) Increase response accuracy  
B) Work together with temperature to control randomness  
C) Reduce the number of tokens  
D) Change the response tone  

**Correct Answer**: B) **Work together with temperature to control randomness ** 

---
**Question:25**
How is a conservative text generation achieved to prioritize predictability and coherence?

A) Temperature 0.9, Top-P 0.99, Top-K 40  
B) Temperature 0.2, Top-P 0.95, Top-K 30  
C) Temperature 0.1, Top-P 0.9, Top-K 20  
D) Temperature 0.3, Top-P 0.8, Top-K 15  

**Correct Answer**: C) Temperature 0.1, Top-P 0.9, Top-K 20  

---
**Question:26**
How is a creative text generation achieved to maximize diversity and originality in output?

A) Temperature 0.1, Top-P 0.9, Top-K 20  
B) Temperature 0.5, Top-P 0.85, Top-K 25  
C) Temperature 0.2, Top-P 0.95, Top-K 30  
D) Temperature 0.9, Top-P 0.99, Top-K 40  

**Correct Answer**: D) **Temperature 0.9, Top-P 0.99, Top-K 40**

---
**Question:27**
How is a balanced text generation achieved to ensure a mix of coherence and controlled randomness?

A) Temperature 0.1, Top-P 0.9, Top-K 20  
B) Temperature 0.2, Top-P 0.95, Top-K 30  
C) Temperature 0.9, Top-P 0.99, Top-K 40  
D) Temperature 0.5, Top-P 0.85, Top-K 25  

**Correct Answer**: B) **Temperature 0.2, Top-P 0.95, Top-K 30** 


---

**Question:28**
What is zero-shot prompting in the context of AI models?

A) Providing multiple examples to guide the model's response  
B) Asking the model directly without providing examples  
C) Training the model on a specific dataset before querying  
D) Using complex prompts with detailed instructions  

**Correct Answer**: B) **Asking the model directly without providing examples**  

---
**Question:29**
When is zero-shot prompting most appropriate to use?

A) When the task requires extensive training data  
B) For simple, well-defined tasks with clear model knowledge  
C) When the model needs multiple examples to understand the task  
D) For tasks requiring high computational resources  

**Correct Answer**: B) **For simple, well-defined tasks with clear model knowledge**  

---
**Question:30**
What is one-shot prompting in the context of AI models?

A) Asking the model without any examples or guidance\
B) Providing a single example to guide the response format\
C) Training the model with multiple examples before querying\
D) Using complex instructions without any examples

**Correct Answer**: B) **Providing a single example to guide the response format**

---
**Question:31**
What is the main purpose of few-shot prompting?

A) To confuse the model with random examples
B) To show the model a pattern using multiple examples
C) To reduce the number of examples given
D) To make the model forget previous examples

**Answer:** B

---
**Question:32**
In few-shot prompting, what do the examples help the model understand?

A) The internet connection speed
B) The pattern or format expected in the output
C) The training dataset of the model
D) The programming language used

**Answer:** B

---
**Question:33**
In the given example, what format does the output follow?

A) Paragraph text\
B) XML data\
C) JSON format\
D) CSV format

**Answer:** C

---

**Question:34**

Few-shot prompting is especially useful when:

A) The model already knows everything\
B) You want the model to learn a new pattern through examples\
C) You want random answers\
D) You are using no instructions

**Answer:** B

---

**Question:36**
How many examples should you typically use in few-shot prompting?
A) Only 1 example\
B) 3–5 examples\
C) 10–15 examples\
D) As many as possible

**Answer:** B


---

**Question:35**
1. What is the main purpose of a system prompt?

A) To format data into JSON\
B) To set the model’s overall context and behavior\
C) To generate random answers\
D) To limit the number of responses

**Answer:** B

---

**Question:36**
What is the main purpose of role prompting?

A) To assign a specific character or expertise to the AI\
B) To format answers in JSON\
C) To limit the model’s vocabulary\
D) To make the AI answer shorter

**Answer:** A

---

**Question:37**
How does assigning a role help the AI?

A) It helps the AI respond with the right tone, expertise, and style\
B) It reduces the response length\
C) It disables the model’s memory\
D) It hides system instructions

**Answer:** A

---

**Question:38**
Which of the following is an example of a communication style role?

A) Data analyst
B) Friendly tutor
C) Software engineer
D) Doctor

**Answer:** B

---

**Question:39**
What is the main goal of contextual prompting?

A) To provide background information relevant to the task
B) To confuse the model with random data
C) To assign a specific role to the AI
D) To shorten the prompt

**Answer:** A

---

**Question:40**
Why is context important in prompting?

A) It helps the model give more accurate and relevant answers
B) It makes responses longer for no reason
C) It reduces the AI’s understanding
D) It hides the real task from the model

**Answer:** A

---

**Question:41**
What is the purpose of Chain-of-Thought prompting?

A) To shorten the answer only
B) To encourage step-by-step reasoning for complex problems
C) To hide steps from the user
D) To force the model to output JSON only

**Answer:** B

---

**Question:42**
CoT prompting is most useful for which of the following?

A) Single-word translations
B) Math problems, logical reasoning, and multi-step analysis
C) Changing font sizes
D) Generating random names

**Answer:** B

---

**Question:43**
Which instruction is a good CoT prompt starter?

A) “Answer in one word.”
B) “Solve this step by step:”
C) “Give me only the final number.”
D) “Make it short and vague.”

**Answer:** B

---

**Question:44**
Which phrase is recommended to trigger step-by-step reasoning?

A) “Answer in one word”\
B) “Let’s think step by step”\
C) “Be brief”\
D) “Ignore the steps”

**Answer:** B

---

**Question:45**
Why set temperature to 0 for CoT tasks?

A) To make outputs more creative\
B) To shorten responses\
C) To make reasoning consistent and deterministic\
D) To randomize answers

**Answer:** C

---

**Question:46**
What is the main purpose of Self-Consistency prompting?

A) To generate random answers each time\
B) To test the model’s creativity\
C) To generate multiple reasoning paths and select the most consistent answer\
D) To reduce the number of reasoning steps

**Answer:** C

---

**Question:47**
What should you do to apply Self-Consistency effectively?

A) Ask the question once only
B) Ask the same question multiple times with different phrasings
C) Change the topic each time
D) Avoid comparing results

**Answer:** B

---

**Question:48**
What is the key step after generating multiple reasoning paths?

A) Use the longest answer\
B) Choose the most emotional answer\
C) Select the most frequently occurring result\
D) Randomly pick one result

**Answer:** C

---

**Question:49**
What kind of problems benefit most from Self-Consistency prompting?

A) Simple yes/no questions\
B) Complex reasoning or analytical tasks that require accuracy\
C) Random text generation\
D) Grammar correction tasks

**Answer:** B

---

**Question:50**
What is the main goal of Step-Back Prompting?

A) To make the model answer faster\
B) To ask a more general question first, then use that context for the specific question\
C) To remove all context from the prompt\
D) To avoid reasoning steps

**Answer:** B

---

**Question:51**

What does “ReAct” stand for?
A) Reacting quickly to user input
B) Reasoning + Acting
C) Research + Action Tool
D) Recursive Activity

**Answer:** B

---
**Question:52**

2. What are the three key components in the ReAct process?
A) Search, Read, Write
B) Plan, Execute, Finish
C) Thought, Action, Observation
D) Input, Output, Feedback

**Answer:** C

---

**Question:53**

3. What is the main purpose of ReAct prompting?
A) To create random actions without reasoning
B) To make the AI output faster
C) To combine reasoning with tool use for solving complex, real-world tasks
D) To remove all external information

**Answer:** C