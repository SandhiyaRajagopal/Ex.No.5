

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

# OUTPUT

# Q&A Pattern with Test Scenarios
# Q1. What is the objective of comparing prompting patterns in maintenance report generation?

Answer:
The objective is to determine which prompting technique (straightforward, tabular, missing word, preceding question, etc.) produces the most accurate, structured, and context-aware maintenance reports for industrial equipment, especially when the input varies from vague descriptions to precisely defined prompts.

# Q2. What prompting techniques are being compared?

Answer:

Straightforward Prompting – Direct, simple question or instruction.

Tabular Format Prompting – Information structured in rows/columns for clarity.

Missing Word Prompting – Filling blanks to guide structured output.

Preceding Question Prompting – Asking a leading/context-setting question before the main query.

# Q3. Test Scenario 1 – Broad / Unstructured Prompt

Prompt:
“Generate a maintenance report for a machine that had issues yesterday.”

Straightforward Prompting Response: May produce a generic, vague report with missing details.

Tabular Prompting Response: Struggles, since input lacks structured data.

Missing Word Prompting Response: Produces incomplete details, unless guided.

Preceding Question Prompting Response: Adds clarity by first asking: “What type of machine and what specific issues?” leading to better final report.

Analysis: Preceding Question Prompting performs best for vague inputs.

# Q4. Test Scenario 2 – Basic / Refined Prompt

Prompt:
“Generate a maintenance report for Pump #12: Fault – Overheating; Maintenance done – Replaced coolant valve; Status – Running normally.”

Straightforward Prompting Response: Clear, but may lack formatting.

Tabular Format Prompting Response: Excellent structured report (Date, Machine ID, Fault, Action Taken, Status).

Missing Word Prompting Response: Works well if template is “The fault was __, the action taken was __.”

Preceding Question Prompting Response: Less useful since input is already refined.

Analysis: Tabular and Missing Word Prompting perform best for structured inputs.

# Q5. Which prompting pattern ensures better accuracy in automated report generation?

Answer:

Structured Prompts (Tabular + Missing Word) → Higher accuracy, as details are placed in fixed fields.

Unstructured Prompts (Straightforward + Preceding Question) → Accuracy depends on how much clarification the model seeks.

# Q6. Which prompting pattern ensures better depth and completeness?

Answer:

Preceding Question Prompting → Encourages deeper exploration by seeking missing details.

Straightforward Prompting → May remain shallow if the input is vague.

# Q7. What is the overall comparative conclusion?

Answer:

For vague/broad prompts → Preceding Question Prompting is best.

For clear/refined prompts → Tabular and Missing Word Prompting yield more structured, accurate reports.

A hybrid approach (preceding question + tabular formatting) offers the most robust performance for real-world automated maintenance systems.


# RESULT: The prompt for the above said problem executed successfully
