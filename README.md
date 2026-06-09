# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:
Define Scope & Dataset

Use Cases: Summarization, Technical Question Answering

Prompts: Designed for both simple and technical contexts

Establish Evaluation Rubric

Metrics: Accuracy, Relevance, Clarity, Depth, Conciseness, Safety

Scale: 1–5 per metric

Generate Outputs

Apply the same prompts across all platforms

Collect outputs and note metadata (time, version)

Evaluation Process

Blind evaluation (platform names hidden)

Human raters scored each output independently

Aggregate Scores

Compute mean values per metric

Calculate composite scores for overall comparison

Analysis

Identify variations in style and quality

Observe tendencies (e.g., concise vs. verbose, technical vs. simple)

Reporting

Include comparative ranking table


## Prompt

## Case 1: Text Summarization

Prompt:
“Summarize the following text into three sentences: Artificial intelligence is rapidly evolving and is transforming industries such as healthcare, education, and finance. However, ethical challenges related to privacy, fairness, and accountability remain critical. Governments, researchers, and companies are working together to ensure responsible deployment of AI.”

ChatGPT Output:
AI is transforming industries like healthcare, education, and finance. Ethical concerns such as privacy, fairness, and accountability remain central. Governments, researchers, and companies collaborate for responsible AI.
Result: Accurate, concise, clear → Excellent

Claude Output:
AI is advancing quickly in sectors like healthcare, education, and finance. This brings ethical concerns over privacy, fairness, and accountability. Governments and companies are working together for safe AI use.
Result: Accurate, polished, slightly less detailed → Very Good

Bard/Gemini Output:
AI is changing industries but creates challenges like fairness and privacy. Governments and companies are seeking solutions. The goal is responsible AI for society.
Result: Correct but oversimplified → Moderate

Cohere Command Output:
AI is spreading into finance, healthcare, and education. Ethical issues—privacy, fairness, accountability—are critical. Governments and companies act to build trust in AI.
Result: Accurate, slightly technical tone → Good

Meta AI Output:
AI affects healthcare, finance, and education. Challenges include privacy and accountability. Governments and researchers aim for safe AI.
Result: Factual but fragmented → Average

## Case 2: Technical Question Answering

Prompt:
“What is the role of power electronics in Vehicle-to-Grid (V2G) systems?”

ChatGPT Output:
Power electronics enable bidirectional energy exchange between EVs and the grid. They manage charging/discharging, ensure voltage regulation, safety, and grid stability.
Result: Detailed, clear, accurate → Excellent

Claude Output:
In V2G, power electronics regulate charging and discharging. They maintain efficiency, safety, and grid compatibility.
Result: Concise, professional, accurate → Very Good

Bard/Gemini Output:
Power electronics allow safe charging and discharging of vehicles. This helps balance the grid.
Result: Too simple, lacks depth → Fair

Cohere Command Output:
Power electronics provide DC–AC conversion, switching, and protection in V2G. They make EVs reliable grid resources.
Result: Technical, strong explanation → Good

Meta AI Output:
V2G uses power electronics for charging, discharging, and conversion with the grid.
Result: Minimal detail, average clarity → Average

## Case 3: Renewable Energy Summarization

Prompt:
“Summarize the following passage into a short paragraph: Renewable energy sources, such as solar, wind, and hydropower, are increasingly adopted to reduce dependence on fossil fuels. These energy systems are environmentally friendly, sustainable, and help in reducing carbon emissions. However, challenges remain in terms of energy storage, grid integration, and cost competitiveness.”

ChatGPT Output:
Renewable energy like solar, wind, and hydropower cut fossil fuel reliance and emissions. They are sustainable but face hurdles with storage, grid integration, and cost.
Result: Balanced, concise, accurate → Excellent

Claude Output:
Solar, wind, and hydropower reduce fossil fuel use and carbon emissions. Despite sustainability, challenges exist in storage, grid integration, and affordability.
Result: Clear, professional tone → Very Good

Bard/Gemini Output:
Renewables replace fossil fuels and cut emissions. They are sustainable but limited by storage and costs.
Result: Concise, beginner-friendly → Good

Cohere Command Output:
Renewable sources such as solar, wind, and hydropower provide sustainable, low-carbon alternatives but are constrained by storage, integration, and economic barriers.
Result: Structured, technical → Very Good

Meta AI Output:
Solar, wind, and hydropower reduce fossil fuel use but face issues of storage, grid integration, and cost.
Result: Factual but shallow → Average
## Case 4: Creative Writing Prompt

Prompt:
“Write a short motivational message for students preparing for exams.”

ChatGPT Output:
Success in exams comes from steady effort, not last-minute stress. Believe in your preparation and stay confident—your hard work will shine through.
Result: Inspiring, empathetic, clear → Excellent

Claude Output:
Exams are a chance to show what you’ve learned. Approach them with calm focus, and remember that perseverance matters more than perfection.
Result: Thoughtful, polished, slightly formal → Very Good

Bard/Gemini Output:
Study well, stay calm, and believe in yourself. You can do it!
Result: Clear, very simple, beginner-friendly → Good

Cohere Command Output:
Student success lies in disciplined study, consistent practice, and self-trust. Exams are milestones, not final judgments.
Result: Strong tone, slightly technical phrasing → Good

Meta AI Output:
Work hard, stay calm, and you will succeed in exams.
Result: Correct but too basic, minimal detail → Average

## Case 5: Definition/Concept Explanation

Prompt:
“Explain the concept of Internet of Things (IoT) in simple terms.”

ChatGPT Output:
The Internet of Things (IoT) connects everyday devices—like watches, cars, or home appliances—to the internet so they can share data and work smarter. For example, a smart fridge can track food or a smartwatch can monitor your health.
Result: Accurate, clear, relatable → Excellent

Claude Output:
IoT refers to ordinary objects being connected online so they can communicate and be controlled. It makes systems more efficient, from smart homes to industrial monitoring.
Result: Correct, clear, professional → Very Good

Bard/Gemini Output:
IoT means devices like cars, phones, or lights connect to the internet and talk to each other.
Result: Beginner-friendly, lacks depth → Good

Cohere Command Output:
IoT is a network of connected devices that collect and share data over the internet. It integrates sensors, communication protocols, and cloud platforms for real-time intelligence.
Result: Strong technical explanation, slightly jargon-heavy → Good

Meta AI Output:
IoT connects devices to the internet so they can share information.
Result: Very basic, shallow detail → Average

## Comparison Table:

<img width="3000" height="900" alt="ai_platforms_comparison" src="https://github.com/user-attachments/assets/6197366e-6d39-4a0d-8ec3-c0689aa3b639" />
<img width="2400" height="1500" alt="ai_platforms_avg_performance" src="https://github.com/user-attachments/assets/db241f26-4be1-4691-9460-d0bedcdd3254" />


## Output

ChatGPT:Delivers the most balanced mix of depth, accuracy, and readability. Best for academic, technical, and professional needs.

Claude: Clear and polished outputs, slightly less detailed than ChatGPT. Well-suited for professional contexts.

Cohere Command: Strong on technical depth but somewhat formal; more enterprise-oriented.

Bard/Gemini: Highly concise and easy to understand, ideal for general users but less suited for expert-level needs.

Meta AI: Provides functional responses but lacks depth and richness.

## Result

From the comparative evaluation of prompting tools across five AI platforms (ChatGPT, Claude, Cohere Command, Bard/Gemini, and Meta AI), the following results were obtained:

ChatGPT ranked the highest overall, providing the most accurate, clear, and balanced responses across both summarization and technical Q&A tasks.

Claude followed closely, producing polished and professional outputs, though slightly less detailed than ChatGPT.

Cohere Command performed strongly in technical explanations, showing enterprise-oriented precision, but sometimes lacked conversational clarity.

Bard/Gemini was highly concise and beginner-friendly, making it suitable for simple explanations, though it lacked depth for advanced use cases.

Meta AI delivered functional but shallow outputs, often oversimplified and less detailed compared to others.

Final Ranking:

⭐ ChatGPT

⭐ Claude

⭐ Cohere Command

⭐ Bard/Gemini

⭐ Meta AI


