# EXP 5 – Comparative Analysis of Different Types of Prompting Patterns

---

### DATE: 27-09-25 
### REGISTER NUMBER: 212222060030

---

## Aim
To **test and compare how different prompt patterns** influence AI output quality. Specifically, to analyze **naïve (broad/unstructured) prompts** versus **basic (clear, refined) prompts** across multiple test scenarios, focusing on:

- **Quality**  
- **Accuracy**  
- **Depth of responses**

---

## Introduction
Prompt engineering is critical for guiding AI models effectively. The **structure and clarity** of prompts often determine:

- How well the model understands the task  
- The relevance of the generated output  
- The depth of reasoning or creativity in responses  

This experiment explores **naïve prompts** (broad, unstructured) versus **basic prompts** (clear, detailed, structured) using **ChatGPT**, across multiple scenarios.

---

## AI Tools Required
- **ChatGPT** (any version supporting text generation)  
- Optional: **GPT-4 / Claude / Bard** for comparison  

---

## Definitions of Prompt Types

### 1️⃣ Naïve Prompt
- Broad, general, or unstructured  
- Minimal guidance for the model  
- Example:  
  - Scenario: Writing a story  
  - Prompt: `Write a story.`  

### 2️⃣ Basic Prompt
- Clear, structured, and detailed  
- Provides context, instructions, and expected format  
- Example:  
  - Scenario: Writing a story  
  - Prompt: `Write a 200-word story about a young scientist who discovers a new planet. Include the main character's feelings and describe the planet's environment.`

---

## Procedure

### Step 1: Prepare Test Scenarios
Select **multiple AI tasks** to test:

1. **Creative Story Generation**  
2. **Factual Question Answering**  
3. **Article/Concept Summarization**  
4. **Advice or Recommendation**  
5. **Technical Explanation**

For each scenario, create **one naïve prompt** and **one basic prompt**, targeting the same task but with varying structure.

---

### Step 2: Run Experiments with ChatGPT
- Input **naïve prompt** → record AI output  
- Input **basic prompt** → record AI output  
- Repeat for all scenarios  

---

### Step 3: Evaluate Responses
Analyze outputs based on:

| Criterion          | Description                                                        |
|-------------------|--------------------------------------------------------------------|
| Quality            | How well-written and relevant is the response?                     |
| Accuracy           | Does the response reflect correct information?                      |
| Depth              | How detailed, insightful, or creative is the response?             |

---

## Test Scenarios & Prompt Examples

### Scenario 1: Creative Story
| Prompt Type | Prompt |
|------------|--------|
| Naïve      | Write a story. |
| Basic      | Write a 200-word story about a young scientist who discovers a new planet. Include emotions and environment description. |

**Observation:**  
- Naïve: Generic, lacks detail, minimal narrative depth  
- Basic: Rich, vivid descriptions, logical plot, character emotions clearly conveyed

---
<img width="1024" height="1024" alt="unnamed" src="https://github.com/user-attachments/assets/52e4577b-8b9c-44c7-bfef-6fcafead3986" />

### Scenario 2: Factual Question
| Prompt Type | Prompt |
|------------|--------|
| Naïve      | Tell me about photosynthesis. |
| Basic      | Explain photosynthesis in 5 steps, mentioning sunlight, water, carbon dioxide, and glucose formation, suitable for a high school student. |

**Observation:**  
- Naïve: Short answer, some key points missing  
- Basic: Structured, accurate, stepwise explanation

---
<img width="1024" height="1024" alt="unnamed (1)" src="https://github.com/user-attachments/assets/de7ec0cc-76cd-4bf9-bf05-ddf9d1e6f0ba" />

### Scenario 3: Article/Concept Summarization
| Prompt Type | Prompt |
|------------|--------|
| Naïve      | Summarize this article about climate change. |
| Basic      | Summarize this 1000-word article about climate change in 5 bullet points, highlighting causes, effects, and mitigation strategies. |

**Observation:**  
- Naïve: General summary, misses critical insights  
- Basic: Concise, informative, well-organized

---
<img width="1024" height="1024" alt="unnamed (2)" src="https://github.com/user-attachments/assets/c02481c1-9bb7-4572-beed-377d4818c897" />

### Scenario 4: Advice / Recommendation
| Prompt Type | Prompt |
|------------|--------|
| Naïve      | Give advice on healthy eating. |
| Basic      | Provide a weekly diet plan for a 25-year-old adult aiming to gain muscle, including protein, carb, and fat recommendations. |

**Observation:**  
- Naïve: Generic advice, lacks specificity  
- Basic: Actionable, detailed, realistic plan

---

### Scenario 5: Technical Explanation
| Prompt Type | Prompt |
|------------|--------|
| Naïve      | Explain blockchain. |
| Basic      | Explain blockchain technology in simple terms with a 3-step example showing how transactions are verified, stored, and secured. |

**Observation:**  
- Naïve: Simplistic and vague  
- Basic: Stepwise, easy to understand, technical accuracy maintained

---

## Comparative Analysis Table

| Scenario                  | Naïve Prompt Output                    | Basic Prompt Output                         | Quality | Accuracy | Depth | Insights |
|---------------------------|---------------------------------------|-------------------------------------------|--------|---------|-------|----------|
| Creative Story            | Generic, minimal plot                 | Rich story, emotional, detailed           | Low    | Medium  | Low   | Basic prompt produces immersive narrative |
| Factual Question          | Partial information                    | Stepwise complete answer                   | Medium | High    | Medium| Basic prompts ensure completeness |
| Article Summarization     | General summary                        | Structured bullet points                    | Medium | High    | High  | Clearer key points in basic prompt |
| Advice / Recommendation   | Vague, generic                          | Detailed weekly plan                        | Medium | High    | High  | Actionable guidance with basic prompt |
| Technical Explanation     | Simplistic, partial                     | Accurate, stepwise example                  | Medium | High    | High  | Structured prompts yield better understanding |

---

## Process Flow Diagram

mermaid
flowchart TD
    A[Define Test Scenarios] --> B[Design Naïve Prompts]
    A --> C[Design Basic Prompts]
    B --> D[Input to ChatGPT]
    C --> D
    D --> E[Record Outputs]
    E --> F[Evaluate using Quality, Accuracy, Depth]
    F --> G[Compare Results]


## Observations & Insights

Basic prompts consistently outperform naïve prompts in quality, depth, and accuracy.

Naïve prompts can occasionally produce good results for very simple tasks but are unreliable for structured outputs.

Structured instructions help AI models focus on key points, organize output, and provide detailed reasoning.

Use of bullet points, word limits, and stepwise instructions in basic prompts enhances clarity.

## Recommendations

Always define context and expectations in prompts.

Include specific instructions or constraints for structured tasks.

Use stepwise or bullet formats for technical or multi-step outputs.

For creative tasks, include word limits, emotions, or scene descriptions to guide narrative.

Avoid broad/unstructured prompts when accuracy and depth are critical.

## Conclusion

The comparative experiment demonstrates that prompt clarity, structure, and detail directly affect AI output.

Naïve prompts: Quick but inconsistent results

Basic prompts: Reliable, high-quality, structured, and in-depth results

Effective prompt engineering ensures better performance, reduced errors, and actionable AI outputs, making it a crucial skill for all AI interactions.

## Result

The experiment successfully executed both naïve and basic prompts across multiple scenarios.
Basic prompts consistently yielded superior quality, accuracy, and depth.

Hence, the comparative analysis validates the importance of prompt clarity and structure for optimal AI performance.
