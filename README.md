# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
Identify different prompt types (broad, basic, refined, few-shot).

Select test scenarios, e.g., automated test scripts, bug identification, and performance testing.

Apply each prompt type to the scenarios and document the AI responses.

Evaluate outputs through criteria: clarity, accuracy, depth, and relevance.

Compare results and analyze which prompting styles yield the best results.

## Output:
Example Comparative Test
Scenario 1: Automated Test Script Generation
Broad Prompt: "Generate a test script for login."

Output: Very generic script mostly checking if login page opens, lacks coverage of edge cases or error handling.

Basic Prompt: "Generate an automated test script to verify valid and invalid logins."

Output: Script covers successful login and some invalid login attempts, but minimal detail on test cases.

Refined Prompt: "Create an automated test script for web login that verifies user authentication with valid credentials, invalid passwords, and includes error message validation for empty inputs and locked accounts."

Output: Detailed script covering positive and negative cases, validations of messages, and edge conditions.

Scenario 2: Bug Identification in Test Cases
Broad Prompt: "Check this test case for bugs."

Output: General remarks often missing specific insight or potential edge cases.

Basic Prompt: "Analyze the login test case and point out any missing edge cases."

Output: Identifies some missing scenarios such as password reset but does not cover full depth.

Refined Prompt: "Review the login test case and identify all potential bugs and edge cases including invalid inputs, SQL injection attacks, session timeouts, and concurrent login attempts."

Output: Comprehensive identification of vulnerabilities and missing cases with actionable suggestions.

Scenario 3: Performance Test Planning
Broad Prompt: "Write a performance test plan."

Output: Vague, high-level description of performance testing without specifics.

Basic Prompt: "Create a performance test plan for a website."

Output: Basic plan including load testing and response time metrics but lacks detail on scenarios and tools.

Refined Prompt: "Design a detailed performance test plan for an e-commerce website simulating 1000 concurrent users, including load distribution, peak traffic times, response time goals, and failure recovery steps."

Output: Well-defined plan with clear metrics, user loads, timing scenarios, and contingency measures.

Comparative Analysis
Prompt Type	Clarity	Accuracy	Depth	Relevance
Broad/Unstructured	Low	Low	Low	Low
Basic Prompts	Medium	Medium	Medium	Medium
Refined/Structured	High	High	High	High
Few-Shot Prompts	High	High	High	High (critical for code generation, bug finding, classification)
Result


## Result
Refined, structured prompts lead to clearer, more accurate, and context-sensitive AI outputs in software testing scenarios. This shows the importance of precise prompt design in improving quality and usefulness in practical AI-assisted testing.
