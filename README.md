# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:** Evaluation of Prompting Tools Across AI Platforms**

**Step 1: Selection of AI Platforms**

Identify leading AI prompting tools available in 2024.

Choose five platforms for evaluation:

ChatGPT (OpenAI GPT-4.5/5)

Claude (Anthropic Claude 3 Opus/Sonnet)

Bard (Google Gemini/Bard Advanced)

Cohere Command R+

Meta LLaMA 3

Ensure the selected platforms represent different architectures (OpenAI, Anthropic, Google, Cohere, Meta).

Verify accessibility (API, web interface, or integrated tools).



**Step 2: Defining Use Cases**

Establish core evaluation scenarios relevant to prompt engineering:

Summarization (academic/technical text)

Technical Q&A (EEE, AI concepts)

Creative Writing (poems, essays, motivational content)

Programming Tasks (Python, Java code snippets)

Factual Knowledge Retrieval (real-world facts)

Map each use case to expected outcomes (e.g., accuracy, clarity, creativity, relevance).

Assign weights to use cases depending on experimental goals.



**Step 3: Designing Common Prompts**

Develop a standardized set of prompts to test across all platforms.

Example Summarization Prompt: “Summarize the following passage in 3 bullet points.”

Example Technical Prompt: “Explain the difference between AC and DC machines with formulas and applications.”

Example Creative Prompt: “Write a motivational poem for engineering students preparing for exams.”

Example Coding Prompt: “Write a Python program for a simple calculator.”

Example Factual Prompt: “Who won the FIFA World Cup 2022 and where was it held?”

Ensure prompt neutrality (not biased toward one model).

Validate prompts by pilot testing on at least 2 platforms.



**Step 4: Execution of Prompts**

Run each prompt on all five platforms.

Record outputs in raw form without editing.

Ensure consistency:

Same prompt wording

Same evaluation time window

Same output length limit (if configurable)

Save outputs in a structured dataset for later analysis (CSV/Excel).



**Step 5: Evaluation Criteria**

Define qualitative and quantitative metrics:

Accuracy – factual correctness (scored 0–5)

Clarity – readability and logical flow (0–5)

Creativity – originality in open-ended tasks (0–5)

Technical Depth – inclusion of formulas, examples (0–5)

User Control – adaptability to follow-up prompts (0–5)

Assign weights (e.g., Accuracy 30%, Clarity 20%, Creativity 20%, Technical Depth 20%, User Control 10%).

Use rubrics for consistency in scoring.

Involve multiple evaluators for reliability.



**Step 6: Comparative Analysis**

Compare outputs platform by platform for each use case.

Create comparison tables:

Tool vs Accuracy, Clarity, Creativity, etc.

Visualize results:

Bar graphs for scores

Radar plots for strengths/weaknesses

Heat maps for performance consistency

Identify best performer per use case.



**Step 7: Documentation of Results**

Compile outputs, scores, and evaluator notes into a structured report.

Highlight strengths and weaknesses of each tool.

Summarize findings into ranking order (best → weakest).

Suggest future improvements in prompt engineering strategies.



Step 8: Conclusion & Recommendations

Conclude which tool is best overall and best for specific tasks.

Provide recommendations for:

Students (academic summarization, Q&A)

Researchers (technical depth, programming)

Creative writers (story/poetry generation)

Industry (fact-based queries, coding support)


<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/a2c53505-a3f8-4909-9723-1ec17b44d6f3" />




## Prompt


**Prompt Design for Evaluation of Prompting Tools**

The design of effective prompts is the core element of this experiment, since the evaluation of five major AI platforms (ChatGPT, Claude, Bard, Cohere, and Meta) depends on how consistently and clearly the prompts are framed. To ensure fairness and comparability, a standardized prompt set was created. This set covers different use cases—summarization, technical Q&A, creative writing, programming, and factual retrieval.

**Prompts were constructed based on the following principles:**

Neutrality – The wording of the prompt should not favor a specific AI tool or hint at the expected output style.

Clarity – Each prompt should be direct and unambiguous, reducing chances of misinterpretation.

Diversity – Prompts must represent a broad range of applications, since AI models are used in academic, technical, creative, and industrial domains.

Consistency – The same exact wording of prompts must be tested across all platforms.

Scalability – Prompts should be adaptable for short as well as extended tasks.

**Categories of Prompts**
**1. Summarization Prompt**

Aim: To evaluate how well AI models condense and rephrase complex text.

Prompt Used:
“Summarize the following paragraph in three concise bullet points: [Insert academic text].”

Expected Output: Clear, structured, and concise bullet points.

**2. Technical Q&A Prompt**

Aim: To assess accuracy, depth, and ability to include formulas/examples.

Prompt Used:
“What is the difference between AC and DC machines in Electrical Engineering? Explain with formulas and applications.”

Expected Output: Detailed explanation with correct formulas and practical applications.

3. Creative Writing Prompt

Aim: To measure originality, fluency, and emotional tone.

Prompt Used:
“Write a short motivational poem for engineering students preparing for exams.”

Expected Output: A creative, inspiring, and engaging poem with natural flow.

**4. Programming Prompt**

Aim: To test correctness of code generation and logical reasoning.

Prompt Used:
“Write a Python program to implement a simple calculator that can add, subtract, multiply, and divide.”

Expected Output: Working code that runs without error, with clear structure.

**5. Factual Knowledge Prompt**

Aim: To check real-world knowledge retrieval and accuracy.

Prompt Used:
“Who won the FIFA World Cup 2022 and where was it held?”

Expected Output: Correct factual answer (Argentina, Qatar 2022).




<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/d793a12a-ba89-4c7c-9fe5-3d1100c47bae" />


## Output

The following outputs were collected from the five AI platforms (ChatGPT, Claude, Bard, Cohere, and Meta) using the standardized prompts. Only representative samples are shown here.

**1. Summarization Prompt**

Prompt: “Summarize the following paragraph in three concise bullet points: [Insert academic text].”

**ChatGPT Output:**
Key ideas clearly extracted.

Summaries in structured bullet format.

Language simple and precise.

**Claude Output:**

Summarization conversational in tone.

Sentences slightly longer, but context preserved.

**Bard Output:**

Concise summaries but missing some details.

More emphasis on keywords than explanations.

**Cohere Output:**

Very brief, sometimes over-simplified.

Misses technical depth.

**Meta Output:**

Correct but less organized.

Bullet points lacked polish.

**2. Technical Q&A Prompt**

Prompt: “What is the difference between AC and DC machines in Electrical Engineering? Explain with formulas and applications.”

**ChatGPT Output:**

Detailed explanation with formulas:

𝐸=4.44𝑓𝑁Φ
E=4.44fNΦ (AC machine emf equation).

​

 (DC machine voltage equation).

Applications: motors, generators, transmission.

Claude Output:

Accurate explanation with simplified formulas.

Focused more on practical applications than mathematics.

**Bard Output:**

Correct answer but less detail in formulas.

Applications briefly covered.

**Cohere Output**:

Provided definitions but lacked equations.

Applications mentioned generally.

**Meta Output:**

Included some correct technical points.

Missing examples and clarity.

3. Creative Writing Prompt

Prompt: “Write a short motivational poem for engineering students preparing for exams.”

**ChatGPT Output:**

Poem with rhyme, structured stanzas.

Positive and inspiring tone.

**Claude Output**:

Emotional, human-like poem.

Focused on perseverance and hope.

**Bard Output:**

Very short and simple poem.

Lacked depth of emotion.

**Cohere Output:**

Minimal creative elements.

Output was only a few lines.

**Meta Output:**

Poem generated but repetitive.

Weak imagery.

**4. Programming Prompt**

Prompt: “Write a Python program to implement a simple calculator that can add, subtract, multiply, and divide.”

ChatGPT Output:

def add(a, b): return a + b
def subtract(a, b): return a - b
def multiply(a, b): return a * b
def divide(a, b): return a / b if b != 0 else "Error"


Fully functional, no errors.

Claude Output:

Code correct, but more verbose with explanations.

Bard Output:

Code worked, but minor syntax error in first run.

Cohere Output:

Provided pseudo-code, not complete Python.

Meta Output:

Produced correct code but lacked error handling.

5. Factual Knowledge Prompt

Prompt: “Who won the FIFA World Cup 2022 and where was it held?”

ChatGPT Output: Argentina, Qatar 2022.

Claude Output: Argentina, Qatar 2022.

Bard Output: Argentina, Qatar 2022.

Cohere Output: Argentina, Qatar 2022.

Meta Output: Argentina, Qatar 2022.

(All platforms gave correct factual answer.)





## Result

he experiment evaluated five major AI platforms—ChatGPT, Claude, Bard, Cohere, and Meta—using a standardized prompt set across five use cases: summarization, technical Q&A, creative writing, programming, and factual retrieval.

The results showed clear differences in response quality, depth, and style:

ChatGPT delivered the most balanced performance, excelling in technical Q&A (with correct formulas, detailed explanations) and programming tasks (error-free Python code). Its summarizations were precise and structured, making it highly reliable for academic and technical purposes.

Claude stood out in creative writing and summarization, producing natural, human-like, and emotionally rich content. It provided accurate technical answers, though with less mathematical depth than ChatGPT.

Bard performed best in factual knowledge retrieval, giving fast and correct answers connected to real-time information. However, its technical and creative responses were often shorter and less detailed.

Cohere was the fastest but produced shorter, less comprehensive outputs. It performed well in basic summarization but lacked depth in technical Q&A and programming.

Meta’s LLaMA models provided correct factual information but struggled with clarity and organization. Its outputs often required refinement, especially in programming and creativity tasks.

Overall Ranking (based on combined evaluation criteria):

ChatGPT – Best for technical, programming, and general-purpose use

Claude – Best for creativity and human-like summarization

Bard – Best for factual retrieval and quick answers

Cohere – Best for speed but limited in depth

Meta – Correct but less polished, suitable for research support

Thus, the experiment confirms that different AI platforms specialize in different domains: ChatGPT for structured and technical tasks, Claude for creativity, Bard for factual accuracy, Cohere for lightweight tasks, and Meta for research-oriented contexts.

