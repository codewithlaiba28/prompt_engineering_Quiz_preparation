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

What are the three key components in the ReAct process?
A) Search, Read, Write
B) Plan, Execute, Finish
C) Thought, Action, Observation
D) Input, Output, Feedback

**Answer:** C

---

**Question:53**

What is the main purpose of ReAct prompting?
A) To create random actions without reasoning
B) To make the AI output faster
C) To combine reasoning with tool use for solving complex, real-world tasks
D) To remove all external information

**Answer:** C

---

**Question:54**

What is the main goal of the Tree of Thoughts (ToT) approach?
A. To memorize large datasets\
B. To explore multiple reasoning paths before reaching a conclusion\
C. To increase the model’s response speed\
D. To use fewer prompts for efficiency
**Answer:** B

---

**Question:55**

Which of the following best describes a “branch” in the ToT framework?

A. A random thought by the model\
B. A different reasoning path exploring one possible solution\
C. The final summarized answer\
D. A prompt used for training
**Answer:** B

---

**Question:56**

Tree of Thoughts (ToT) is especially useful for:

A. Simple factual questions\
B. Tasks with one correct answer\
C. Complex and creative problem solving\
D. Grammar correction tasks

**Answer**: C

---

**Question:57**

Which of the following is the best example of a clear and specific prompt?

A. Write about dogs./
B. Describe dogs.\
C. Write a short note on dogs.\
D. Write a 300-word article about the health benefits of owning a dog, focusing on mental health, physical activity, and social connections.

**Correct Answer:** D. Write a 300-word article about the health benefits of owning a dog, focusing on mental health, physical activity, and social connections.

---

**Question:58**

Why should you use action verbs in prompts?

A. To make the prompt sound longer\
B. To clearly tell the AI what action to perform\
C. To make the output more decorative\
D. To limit the response length
**Correct Answer:** B. To clearly tell the AI what action to perform

---

**Question:59**

Which of the following words is not an action verb used in prompt engineering?

A. Compare\
B. Evaluate\
C. Sleep\
D. Summarize

**Correct Answer:** C. Sleep

---

**Question:60**

What is the benefit of providing examples in your prompt?

A. It makes the prompt shorter\
B. It tells the AI exactly what format and style you expect\
C. It reduces model accuracy\
D. It adds unnecessary complexity

**Correct Answer:** B. It tells the AI exactly what format and style you expect

---

**Question:61**

Which version follows the principle of “Use Instructions Over Constraints”?

A. Write an email but don’t make it too long or too informal.\
B. Write a professional email summarizing the key points from our meeting.\
C. Write something about our meeting.\
D. Avoid long sentences in your email.
**Correct Answer:** B. Write a professional email summarizing the key points from our meeting.

---

**Question:62**

How can you control the output format in a prompt?

A. By limiting the temperature\
B. By specifying the response structure, such as JSON\
C. By avoiding examples\
D. By using fewer instructions
**Correct Answer:** B. By specifying the response structure, such as JSON

---

**Question:63**

What is the main advantage of using variables like {expertise} or {document_type} in prompts?

A. To make prompts reusable and adaptable\
B. To make the text longer\
C. To confuse the AI model\
D. To make the output unpredictable

**Correct Answer:** A. To make prompts reusable and adaptable

---

**Question:64**

What should you do after identifying a successful prompt?

A. Forget it\
B. Keep using the same prompt without changes\
C. Document and test variations to improve it\
D. Delete it immediately

**Correct Answer:** C. Document and test variations to improve it

---

**Question:65**

What is the main issue caused by ambiguous instructions in a prompt?

A. The model refuses to respond\
B. The response becomes too long\
C. The output becomes unpredictable or unclear\
D. The response is always the same

**Correct Answer:** C. The output becomes unpredictable or unclear

---

**Question:66**

How can you avoid ambiguous instructions?

A. Add more random details\
B. Be specific and clearly state what you want\
C. Use fewer words\
D. Add more examples without instructions

**Correct Answer:** B. Be specific and clearly state what you want

---

**Question:67**

How can you avoid over-constraining your prompts?

A. Use longer instructions\
B. Add more rules\
C. Focus on clear, positive instructions instead of long lists of “don’ts”\
D. Remove all formatting

**Correct Answer:** C. Focus on clear, positive instructions instead of long lists of “don’ts”

---

**Question:68**

What is the best way to improve prompt performance over time?

A. Keep using the first version of your prompt\
B. Test different phrasings, examples, and structures\
C. Use fewer instructions\
D. Avoid reviewing results

**Correct Answer:** B. Test different phrasings, examples, and structures

---

**Question:69**

In the provided example, what change was made between version v1.0 and v1.1?

A. Added tone guidance to improve the output\
B. Changed model from GPT-4 to GPT-3\
C. Reduced temperature\
D. Removed output quality rating

**Correct Answer:** A. Added tone guidance to improve the output

---

**Question:70**

What is the main purpose of a testing framework in prompt engineering?
A. To randomly test prompts for fun\
B. To systematically record, analyze, and improve prompt performance\
C. To generate prompts automatically without testing\
D. To reduce the model’s accuracy

**Correct Answer:** B. To systematically record, analyze, and improve prompt performance

---

**Question:71**

Which of the following is NOT a key element of a testing framework?

A. Recording prompt variations\
B. Evaluating results\
C. Ignoring feedback\
D. Refining prompts based on insights

**Correct Answer:** C. Ignoring feedback

---

**Question:72**

What should be recorded in a prompt testing framework?

A. Prompt versions, goals, model, temperature, output quality, and notes\
B. Only the model name\
C. Only the date of testing\
D. Only the temperature value

**Correct Answer:** A. Prompt versions, goals, model, temperature, output quality, and notes

---

**Question:73**

What kind of output qualities are usually compared in A/B testing?

A. Accuracy, relevance, and quality\
B. File size and font style\
C. Response time only\
D. Number of tokens used


**Correct Answer:** A. Accuracy, relevance, and quality

---

**Question:74**

What is the benefit of running A/B tests on prompts?

A. To test random prompts\
B. To find which prompt version produces the most effective and consistent output\
C. To reduce creativity\
D. To save API costs


**Correct Answer:** B. To find which prompt version produces the most effective and consistent output

---

**Question:75**

What is the main purpose of A/B testing in prompt engineering?

A. To test AI models from different companies
B. To compare multiple prompt versions and identify which performs best
C. To randomly change prompts for variety
D. To test temperature limits only


**Correct Answer:** B. To compare multiple prompt versions and identify which performs best

---

**Question:76**

What is the main goal of evaluating AI-generated results?

A.To see how fast the AI responds\
B. To measure the quality and effectiveness of the output\
C. To reduce token usage\
D. To compare different models


**Correct Answer:** B. To measure the quality and effectiveness of the output

---

**Question:77**

What does consistency mean in prompt evaluation?

A. The same prompt should produce similar outputs across multiple runs\
B. The AI should generate random answers\
C. The tone should always change\
D. The output must include examples

**Correct Answer:** A. The same prompt should produce similar outputs across multiple runs

---

**Question:77**

What should a prompt engineer include to improve context management during long conversations?

A. Unrelated examples\
B. Summaries of previous context\
C. Randomized inputs\
D. Higher temperature

**Correct Answer:** B. Summaries of previous context

---

**Question:78**

What does multi-modal prompting refer to?

A. Using multiple models at once\
B. Combining text with images or other input types\
C. Using random outputs\
D. Asking for JSON responses only

**Correct Answer:** B. Combining text with images or other input types


----

**Question:79**

What is the main goal of prompt chaining?

A. To create longer prompts\
B. To break complex tasks into clear, logical steps\
C. To mix multiple topics\
D. To avoid structured formats

**Correct Answer:** B. To break complex tasks into clear, logical steps

----

**Question:80**

Which advanced technique helps you connect multiple prompts for a single large task?
A. Multi-modal prompting
B. Prompt chaining
C. Structured outputs
D. Context summarization

**Correct Answer:** B. Prompt chaining

---

**Question:81**

What is the main purpose of Mixture-of-Experts (MoE) in large language models (LLMs)?

A. To reduce model parameters\
B. To improve efficiency by activating only relevant experts per input\
C. To train multiple models at once\
D. To simplify model architecture

**Correct Answer:** B. To improve efficiency by activating only relevant experts per input

---

**Question:82**

What is an “expert” in the context of MoE models?

A. A human providing data\
B. A specialized sub-network trained for specific types of tasks or data\
C. A fine-tuned dense model\
D. A transformer encoder

**Correct Answer:** B. A specialized sub-network trained for specific types of tasks or data

---

**Question:83**

Which component decides which experts to activate for a given input?

A. Gating Network (or Router)\
B. Optimizer\
C. Decoder\
D. Tokenizer

**Correct Answer:** A. Gating Network (or Router)

---

**Question:84**

What does sparse activation mean in MoE models?

A. Only a subset of experts are activated per token\
B. All parameters are activated every time\
C. Experts take turns randomly\
D. The model deactivates attention heads

**Correct Answer:** A. Only a subset of experts are activated per token

---

**Question:85**

Which of the following is a key benefit of using MoE?

A. Increased compute cost\
B. Higher efficiency with scalable performance\
C. Slower inference time\
D. Limited specialization

**Correct Answer:** B. Higher efficiency with scalable performance

---

**Question:86**

What should you avoid in MoE prompting to prevent routing confusion?

A. Mixing multiple task types in one prompt\
B. Using explicit domain terms\
C. Adding short examples\
D. Keeping the format structured

**Correct Answer:** A. Mixing multiple task types in one prompt

---



**Question:87**
What is the main reason most people fail to get good results from their prompts?

A. They use too many examples\
B. They ask vague or unclear questions\
C. They use technical language\
D. They make prompts too long

**Correct Answer:** B. They ask vague or unclear questions

---

**Question:88**
Which of the following is a strong action verb suitable for clear prompting?

A. Give\
B. Help\
C. Create\
D. Tell

**Correct Answer:** C. Create

---


**Question:89**
What is the key difference between a bad and good prompt?

A. Length of the question\
B. The use of emojis\
C. Clarity, specificity, and action-based wording\
D. Number of examples

**Correct Answer:** C. Clarity, specificity, and action-based wording

---

**Question:90**
Why should you avoid weak verbs like “give” or “help”?

A. They make prompts too long\
B. They sound unprofessional\
C. They don’t guide the model toward a clear, focused task\
D. They are hard to understand

**Correct Answer:** C. They don’t guide the model toward a clear, focused task

---

**Question:91**
A great prompt usually begins with:

A. A question mark\
B. A polite greeting\
C. A clear, direct command using an action verb\
D. A random idea

**Correct Answer:** C. A clear, direct command using an action verb

---

**Question:92**
What does the phrase “be specific about what you want” mean in prompt design?

A. Give all background details\
B. Clearly define the goal, topic, and output format\
C. Keep prompts general for flexibility\
D. Use short phrases only

**Correct Answer:** B. Clearly define the goal, topic, and output format

---

**Question:93**
In the example: “Recommend a diversified investment strategy for a moderate risk investor saving for a home within 5 years.” Why is this a good prompt?

A. It’s long and polite\
B. It includes a clear goal, context, and time frame\
C. It uses technical terms\
D. It sounds formal

**Correct Answer:** B. It includes a clear goal, context, and time frame

---

**Question:94**

Which of the following best defines a clear prompt?

A. A vague question that allows creativity\
B. A command that directs the model toward a specific and measurable goal\
C. A casual request with multiple meanings\
D. A prompt with no verbs

**Correct Answer:** B. A command that directs the model toward a specific and measurable goal

---


**Question:95**
What is the main purpose of adding context in a prompt?

A. To make the prompt longer\
B. To help AI stay focused and generate relevant responses\
C. To confuse the AI with more information\
D. To test AI’s reasoning ability

**Correct Answer:** B. To help AI stay focused and generate relevant responses

---

**Question:96**
According to the rule “More is Always Better,” what happens if you give too little context?

A. AI becomes faster\
B. AI can take your prompt in any random direction\
C. AI generates detailed answers automatically\
D. AI refuses to respond

**Correct Answer:** B. AI can take your prompt in any random direction


---



**Question:97**
What is the biggest mistake when writing prompts without enough context?

A. The model repeats your input\
B. The model generates off-topic or irrelevant outputs\
C. The model gives too much detail\
D. The model becomes too slow

**Correct Answer:** B. The model generates off-topic or irrelevant outputs

---

**Question:98**
Why is it called the “Rule of Three”?

A. It covers three main elements: Who, What, and When\
B. It uses three words per sentence\
C. It is based on three prompt styles\
D. It applies only to three situations

**Correct Answer:** A. It covers three main elements: Who, What, and When

---


**Question:99**
What is the main problem when you don’t define an output structure in your prompt?

A. The AI may refuse to answer\
B. The AI may respond in a random or unhelpful format\
C. The AI gives only short answers\
D. The AI becomes repetitive

**Correct Answer:** B. The AI may respond in a random or unhelpful format

---

**Question:100**
What is the best way to ensure the AI gives results in a usable format?

A. Use longer prompts\
B. Tell the AI exactly how to format and present the output\
C. Avoid adding examples\
D. Use multiple questions in one prompt

**Correct Answer:** B. Tell the AI exactly how to format and present the output


---


**Question:101**
Which advanced formatting option asks the AI to create a visually shareable result?

A. “Format this as a screenshotable Apple Notes format”\
B. “List all investment types”\
C. “Summarize this in 3 points”\
D. “Write this in paragraph form”

**Correct Answer:** A. “Format this as a screenshotable Apple Notes format”

---

**Question:102**
If you want an output ready to send to someone else, which prompt format is most suitable?

A. “Give me a random list”\
B. “Give me a copy-and-pasteable asset I can send to my partner”\
C. “Explain this briefly”\
D. “Make it short and simple”

**Correct Answer:** B. “Give me a copy-and-pasteable asset I can send to my partner”

---

**Question:103**
What kind of format is best if you want to include multiple data columns?

A. Paragraph\
B. Table\
C. Checklist\
D. Graph

**Correct Answer:** B. Table

---

**Question:104**
What should you do if you plan to *use the AI’s response later* in another project?

A. Ask the AI to generate long explanations\
B. Define a clear, reusable structure for the output\
C. Avoid formatting for flexibility\
D. Skip specifying output type

**Correct Answer:** B. Define a clear, reusable structure for the output

---

**Question:105**
What is the main goal of the Roleplay technique in prompt engineering?

A. To make the AI sound more casual\
B. To define the AI’s expertise and persona for accurate responses\
C. To limit the AI’s creativity\
D. To shorten the prompt length

**Correct Answer:** B. To define the AI’s expertise and persona for accurate responses

---

**Question:106**
How does roleplay affect the AI’s response?

A. It changes who the AI acts as and how it speaks\
B. It only changes the answer length\
C. It removes personality from the response\
D. It limits the AI to yes/no answers

**Correct Answer:** A. It changes who the AI acts as and how it speaks

---

**Question:107**
Which tone modifier would make the AI’s response **realistic and cautious**?

A. “Take a creative and innovative approach”\
B. “Be brutally honest and conservative in your advice”\
C. “Focus on storytelling”\
D. “Write this humorously”

**Correct Answer:** B. “Be brutally honest and conservative in your advice”

---

**Question:108**
If you want a data-focused AI response, which tone modifier is most suitable?

A. “Be friendly and casual”\
B. “Focus on data-driven insights”\
C. “Write this in a poetic tone”\
D. “Be humorous”

**Correct Answer:** B. “Focus on data-driven insights”

---

**Question:109**
What is the main goal of formatting in prompt engineering?

A. To make responses look fancy\
B. To organize information in a clear, actionable way\
C. To reduce the word count\
D. To make AI responses longer

**Correct Answer:** B. To organize information in a clear, actionable way


---


**Question:110**
Why should you end a prompt with “Ask me 10 questions that will help you tailor this strategy even more”?

A. To test AI’s knowledge\
B. To make the model clarify missing details for personalization\
C. To confuse the AI\
D. To make the prompt longer

**Correct Answer:** B. To make the model clarify missing details for personalization

---



**Question:111**
When should you add clarifying questions in a prompt?

A. After combining all elements—command, context, logic, roleplay, and formatting\
B. At the very beginning of your prompt\
C. Only if the AI refuses to answer\
D. When using weak verbs like “give” or “help”

**Correct Answer:** A. After combining all elements—command, context, logic, roleplay, and formatting

----



**Question:112**
What is the main purpose of the Advanced Question Strategy?

A. To make the AI ask random questions\
B. To help the AI gather enough context to deliver the most accurate and personalized response\
C. To make prompts longer for no reason\
D. To confuse the model intentionally

**Correct Answer:** B. To help the AI gather enough context to deliver the most accurate and personalized response

---

**Question:113**

When should you stop using the Advanced Question Strategy?

A. After 5 total questions\
B. When the AI starts repeating questions\
C. After three rounds, no matter what\
D. When the AI gives short answers

**Correct Answer:** B. When the AI starts repeating questions

---

**Question:114**
Why is using **voice memos** recommended during this process?

A. It saves typing time and allows more natural responses\
B. It records the AI’s responses automatically\
C. It makes prompts sound professional\
D. It translates questions into other languages

**Correct Answer:** A. It saves typing time and allows more natural responses

---

**Question:115**
How many questions are generally enough for **simple tasks**?

A. 1–2 questions\
B. 3–5 questions\
C. 10–15 questions\
D. 20–30 questions

**Correct Answer:** B. 3–5 questions

---

**Question:116**
For **major or life-changing decisions**, how many total questions should you go through?

A. 5–10 questions\
B. 10–15 questions\
C. 20–30 questions\
D. 2–3 questions

**Correct Answer:** C. 20–30 questions

---

**Question:117**
Why should you increase the number of questions for complex or high-impact decisions?

A. To test the AI’s patience\
B. To explore all possible factors and ensure high-quality insights\
C. To make the conversation longer\
D. To fill token space

**Correct Answer:** B. To explore all possible factors and ensure high-quality insights


---

**Question:118**
What is one of the biggest mistakes in prompt engineering?

A. Starting with clear directives\
B. Skipping the command and beginning with questions\
C. Adding too much context\
D. Giving a detailed structure

**Correct Answer:** B. Skipping the command and beginning with questions

---

**Question:119**
What happens when you provide **insufficient context** in your prompt?

A. The AI gives a perfectly targeted response\
B. The AI generates vague or generic answers\
C. The AI produces structured tables\
D. The AI becomes faster

**Correct Answer:** B. The AI generates vague or generic answers

---

**Question:120**
Why is defining an **output structure** important?

A. It makes the prompt look long and detailed\
B. It tells the AI exactly how to organize the response\
C. It limits the AI’s creativity\
D. It’s optional for professional prompts

**Correct Answer:** B. It tells the AI exactly how to organize the response

---

**Question:121**
What is the problem with using **generic roles** like “expert” or “professional”?

A. They make the AI too advanced\
B. They don’t guide the AI toward a specific domain of expertise\
C. They slow down AI responses\
D. They improve creativity but reduce clarity

**Correct Answer:** B. They don’t guide the AI toward a specific domain of expertise

---

**Question:122**
Why is it a mistake to **stop too early** in the prompting process?

A. The AI may still have missing information that affects output quality\
B. It wastes more tokens\
C. It adds unnecessary questions\
D. It increases repetition

**Correct Answer:** A. The AI may still have missing information that affects output quality

---

**Question:123**
Which of the following tasks is considered a **personal** use of the framework?

A. Technical documentation\
B. Business plan development\
C. Meal planning and workout routines\
D. Marketing strategy design

**Correct Answer:** C. Meal planning and workout routines

---

**Question:124**
Which task falls under the **professional** application category?

A. Storytelling framework\
B. Research plan\
C. Business plan or marketing strategy\
D. Travel itinerary

**Correct Answer:** C. Business plan or marketing strategy

---


**Question:125**
Creating a **study guide or learning curriculum** is an example of which application type?

A. Creative\
B. Educational\
C. Professional\
D. Personal

**Correct Answer:** B. Educational

---

**Question:126**
What is the **core benefit** of mastering this 6-part framework?

A. It helps automate AI tools\
B. It allows you to control AI’s internal reasoning\
C. It dramatically improves the quality and precision of AI outputs\
D. It increases typing speed

**Correct Answer:** C. It dramatically improves the quality and precision of AI outputs

---

**Question:127**

What is the main goal of Context Engineering?

A) To write prompts in natural language\
B) To train new LLM models\
C) To give the model the right information at the right time\
D) To improve model tokenization

**Answer:** C

---
**Question:128**

What does “context window” refer to in an LLM?

A) The display screen where results are shown\
B) The input area where data and instructions are packed\
C) The neural layer of the model\
D) The dataset used during training

**Answer:** B

---
**Question:129**

In simple terms, Context Engineering is like:

A) Building a model from scratch\
B) Creating a perfect instruction manual for the AI\
C) Training data labeling\
D) Choosing the best dataset

**Answer:** B

---
**Question:130**

Which of the following best describes Context Engineering?

A) Writing short and direct prompts\
B) Designing systems to feed relevant information into the LLM dynamically\
C) Manually correcting AI outputs\
D) Reducing model parameters

**Answer:** B

---

**Question:131**

Why is Context Engineering important?

A) It increases LLM speed\
B) It ensures the AI gets precise and useful data for better results\
C) It replaces prompt engineering completely\
D) It reduces internet dependency

**Answer:** B

---

**Question:132**

According to Andrej Karpathy, what does the context window represent in the LLM analogy?

A) CPU\
B) GPU\
C) RAM\
D) Hard Drive

**Answer:** C

---

**Question:133**

In Karpathy’s comparison, what does the LLM itself represent?

A) Operating System\
B) CPU\
C) Cache\
D) GPU

**Answer:** B

---

**Question:134**

What is the main objective of Context Engineering?

A) To train LLMs from scratch\
B) To optimize how we fill the model’s “RAM” (context window) with the most relevant information\
C) To design hardware for AI systems\
D) To create datasets for pretraining

**Answer:** B

---

**Question:135**

Why is the context window compared to RAM?

A) Because it permanently stores data\
B) Because it temporarily holds information the model can actively use\
C) Because it processes data like a CPU\
D) Because it determines model accuracy

**Answer:** B

---

**Question:136**

Which statement best summarizes Context Engineering?

A) It’s about writing clever prompts only.\
B) It’s about building dynamic systems that feed the LLM the right information in the right format at the right time.\
C) It’s about fine-tuning model weights.\
D) It’s about improving data labeling.

**Answer:** B

---

**Question:137**

What happens if the context window is poorly optimized?

A) The LLM generates faster results.\
B) The LLM receives irrelevant or incomplete data, leading to poor responses.\
C) The LLM’s token usage decreases automatically.\
D) The model retrains itself.

**Answer:** B

---

**Question:138**

**What is the primary use case of Prompt Engineering?**

A) Building AI-powered applications\
B) Direct conversations with AI (like ChatGPT)\
C) Designing LLM architectures\
D) Managing datasets

**Answer:** B

---

**Question:139**

**Which type of engineering is more likely used for creating a customer service or sales assistant agent?**

A) Prompt Engineering\
B) Context Engineering\
C) Data Engineering\
D) Model Training

**Answer:** B

---

**Question:140**

**How does the nature of interaction differ in Prompt Engineering?**

A) It involves one-time, static instructions\
B) It’s a back-and-forth conversational process\
C) It uses XML-like syntax and structured tags\
D) It runs without user interaction

**Answer:** B

---

**Question:141**

**What is a key characteristic of Context Engineering?**

A) Simple question-and-answer format\
B) Uses iterative prompts for refining outputs\
C) Involves complex, structured inputs with markdown or XML tags\
D) Requires no system-level planning

**Answer:** C

---

**Question:142**

**Which statement best describes the complexity difference between the two?**

A) Prompt Engineering is complex; Context Engineering is simple

B) Both are simple techniques

C) Prompt Engineering allows simple refinement, while Context Engineering uses complex, code-like structures

D) Context Engineering relies only on user chat history

**Answer:** C

---

**Question:143**

**What is the “Model” in an AI system?**

A) The user interface of the system\
B) The core AI engine that processes inputs and generates outputs\
C) The storage unit for data\
D) The monitoring dashboard

**Answer:** B

---


**Question:144**

**What is the main function of Tools in AI systems?**

A) To enhance model training\
B) To enable interaction with external systems\
C) To store long-term memory\
D) To control data encryption

**Answer:** B

---

**Question:145**

**What’s the difference between Knowledge and Memory?**

A) Knowledge is static; Memory is dynamic\
B) Both are static\
C) Memory stores pretraining data\
D) Knowledge is short-term; Memory is long-term

**Answer:** A

---

**Question:146**

**What role does “Audio and Speech” play in AI systems?**

A) Adds visual interaction\
B) Provides voice input/output for natural and accessible communication\
C) Improves database speed\
D) Helps in debugging system errors

**Answer:** B

---

**Question:147**

**What are “Guardrails” in AI systems?**

A) Hardware protection units\
B) Safety mechanisms ensuring proper behavior and compliance\
C) Tools for faster API calls\
D) Model fine-tuning scripts

**Answer:** B

---

**Question:148**

**Why is Orchestration important in AI systems?**

A) It trains new models\
B) It ensures continuous improvement and system reliability after deployment\
C) It improves conversation flow\
D) It filters sensitive data

**Answer:** B

---

**Question:149**

What type of content should the assistant avoid in its final summary?

A) Bullet points\
B) Background information, fluff, or personal commentary\
C) New AI updates\
D) Data sources

**Answer:** B

---

**Question:150**

According to the best practices, what is the key to maintaining clarity and consistency in context structure?

A) Using emojis and short phrases
B) Using XML tags, markdown, and clear formatting
C) Adding random separators
D) Keeping everything in plain text

**Answer:** B

---

**Question:151**

Why should you anticipate all possible scenarios when designing a context system?

A) To make it look complex
B) To ensure comprehensive and reliable behavior across different inputs
C) To reduce token usage
D) To shorten the development time

**Answer:** B

---

**Question:152**

What is the main reason for extensive testing of context-engineered systems?

A) To find and handle edge cases that could break the system
B) To increase training data size
C) To improve AI creativity
D) To reduce user feedback

**Answer:** A

---

**Question:153**

Why is continuous iteration based on real usage important?

A) It helps monitor performance and make practical improvements
B) It saves time during initial setup
C) It removes the need for documentation
D) It allows skipping user testing

**Answer:** A

---

**Question:154**

Which of the following ensures safety and trust in context-engineered systems?

A) Using random prompts
B) Implementing proper guardrails and security measures
C) Ignoring user data
D) Limiting context tokens

**Answer:** B

---

**Question:155**

What does context engineering primarily extend or evolve from?

A) Data labeling
B) Prompt engineering
C) Model pruning
D) Frontend design

**Answer:** B

---

**Question:156**

Which goal best describes context engineering for AI agents?

A) Making prompts shorter
B) Architecting comprehensive instruction systems so agents operate effectively and safely
C) Replacing human oversight entirely
D) Increasing model parameter count

**Answer:** B

---

**Question:157**

Why is it important to treat context engineering as an ongoing process?

A) Models never change, so one-time setup is enough
B) The field is rapidly evolving and real-world performance requires iteration
C) To avoid writing documentation
D) Because it reduces the need for testing

**Answer:** B

---

**Question:158**

Which of the following is *not* a core recommendation for getting started with context engineering?

A) Start simple
B) Test thoroughly
C) Iterate based on performance
D) Deploy without monitoring

**Answer:** D

---

**Question:159**

Context engineering aims to enable AI agents to handle:

A) Only trivial chat responses
B) Complex tasks and real-world scenarios
C) Only image generation
D) Only offline batch jobs

**Answer:** B

---

**Question:160**

What is a key risk if context systems are not well-architected?

A) Faster inference
B) Unreliable or unsafe agent behavior in production
C) Reduced model size
D) Lower data storage costs

**Answer:** B

---

**Question:161**

Which practice helps keep context engineering effective as technology changes?

A) Freezing the design once implemented
B) Staying updated with new frameworks, tools, and best practices
C) Avoiding community discussions
D) Using proprietary solutions only

**Answer:** B

---

**Question:162**

What’s the single best first step when beginning a context engineering project?

A) Build a massive multi-module system immediately
B) Start simple and iterate based on testing and real usage
C) Skip testing and rely on intuition
D) Outsource monitoring entirely

**Answer:** B

