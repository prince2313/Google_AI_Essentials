# Discover the Art of Prompt Engineering
## Understand large language models

- **Prompt:**
	- Text input that provides instructions to the AI model on how to generate output.

- Hallucinations:
	- AI outputs that are not true.

- **Few-shot prompting:**
	- A technique that provides two or more examples in a prompt.

- **Factors that can contribute to hallucinations:**
	- Quality of LLM's training data.
	- Phrasing of the prompt.
	- Method an LLM uses.

---
## Prompts for different purposes
### Use cases

- **Content creation**
    - LLM helps create content like blog posts, reports, product descriptions, and taglines.
    - Example: Tagline for a washing machine: 
        - Role: Creative advertising professional
        - Task: Create a concise tagline emphasizing product features.
        - Pro tip: Assign LLM a role to guide output.

- **Summarization**
    - LLM summarizes various texts such as emails, meeting notes, etc.
    - Example: Summarize email:
        - Context: Email from a software vendor
        - Task: Summarize main points in bulleted list format.

- **Classification**
    - LLM categorizes text based on content, sentiment, etc.
    - Example: Analyze sentiment in customer reviews:
        - Task: Determine sentiment (positive, negative, neutral) of reviews.

- **Extraction**
    - LLM extracts data from text and presents it in a structured format.
    - Example: Extract clothing items from blog post:
        - Task: Create bulleted list of clothing items mentioned with prices.

- **Translation**
    - LLM translates text between languages.
    - Example: Translate product descriptions:
        - Task: Translate English product descriptions to Spanish while maintaining tone.

- **Editing**
    - LLM edits and rewrites text for clarity or style.
    - Example: Simplify technical report language:
        - Task: Edit paragraph for general audience comprehension.

- **Problem-solving**
    - LLM generates solutions for various workplace challenges.
    - Example: Organize gardening program:
        - Context: Community program teaching children gardening skills.
        - Steps: 
            1. Identify 10 plants with sources for time to harvest.
            2. Select three diverse plants for children to grow.

---
## Chain-of-Thought Prompting

### Overview

- **Definition**: Technique guiding LLMs through reasoning processes.
- **Use**: Step-by-step reasoning, enhancing output quality.

#### Benefits

1. **Accuracy**: Divides tasks, ensures accuracy.
2. **Problem Solving**: Breaks down problems, aids understanding.

#### Applications

- **Math/Logic**: Solving problems involving reasoning.
- **Examples**: Purchasing decisions, sales analysis, product recommendations.

### Prompt Design

![Stairs that say "context," "example," and "request." The word "output" is below them all.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/WHlrcU3BRT60wRUNX4jPlg_cf794843334f4249afc21dd1c6edc0f1_R-012_Image-2.png?expiry=1717977600000&hmac=wxZYvOjBUPZ3S6EzbsBtAf1Rk9WLGWPi17-Wz2jj3hs)
- **Components**: Context, Example, Request.
- **Objective**: Guide LLMs through problem-solving.

### Example: Creating Purchasing Codes
#### Context

- Describes organization's method for creating purchasing codes.
- Instructs LLMs to follow examples to determine purchasing code.

#### Example

- Presents scenarios with department and ID numbers.
- Q&A format aids understanding.
- Answer explains step-by-step reasoning.

#### Request

- Poses questions similar to examples.
- Blank space for LLMs to fill in answers.

---
## Prompt Engineering Best Practices
### Specify the Task
#### Overview

- Clarify desired output for LLMs.
- Use straightforward language and logical structure.

**Example:** _Draft an informal email to my manager requesting time off._

### Provide Necessary Context
#### Importance of Context

- Shapes LLM responses.
- Clarifies audience, tone, structure, and goal.

**Considerations:**
- Audience
- Tone
- Structure
- Goal

**Example:** _Write a friendly email to my HR coworker thanking them for their collaboration on a recent project so they know their contributions were invaluable._

### Provide References
#### Importance of References

- Aids LLM understanding.
- Helps generate relevant outputs.

**Example:** _Draft a list of potential campaign slogans for a sunglass company in the writing style of 1960s billboard advertisements._

### Evaluate Your Output
#### Importance of Evaluation

- Ensures accuracy, relevance, and consistency.
- Identifies biases and hallucinations.

**Considerations:**
- Accuracy
- Bias
- Sufficiency
- Relevance
- Consistency

**Example:** 
- _What’s a conditional?_
- **Iteration:** _Explain ‘conditionals’ to a beginner coder like a textbook._

### Take an Iterative Approach
#### Importance of Iteration

- Refines prompts based on initial outputs.
- Allows for adjustments and follow-up requests.

**Example:** 
- _Summarize the following meeting notes._
- **Follow-up:** _What were key takeaways from this meeting?_
- **Second follow-up:** _What are the most urgent action items and their deadlines?_

---