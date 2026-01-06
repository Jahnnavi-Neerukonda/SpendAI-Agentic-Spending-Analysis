# SpendAI – Agentic Spending Behavior Analysis Agent
Project Overview (Problem → Solution)

Problem:
Most people track expenses but still don’t understand why they overspend or where habits go wrong. Existing tools focus on numbers, not behavior, and become overwhelming or unusable with incomplete data.

Solution:
SpendAI is an agentic AI prototype built using Gemini AI Studio that analyzes spending data and habit inputs to identify patterns, explain behaviors in simple language, and suggest practical habit improvements with savings awareness—without giving financial or tax advice.

## What SpendAI Does

- Analyzes user-provided expenses (table, text, or step-by-step)
- Uses a short habit quiz to understand spending behavior
- Identifies key spending patterns and unhealthy habits
- Explains why patterns occur in simple, non-technical language
- Suggests small, realistic habit changes that may lead to savings
- Provides high-level tax-awareness areas (region-neutral by default)
- Remains transparent when data is missing or incomplete

## Input → Output Example
### Example Input

- Food: ₹6,000
- Shopping: ₹4,500
- Travel: ₹2,000
- Habit quiz: “I often make impulse purchases” → Yes

### Example Output

- Food and shopping are your highest spending categories
- Spending increases on weekends compared to weekdays
- Delaying non-essential purchases may reduce unnecessary spending
- Some expense entries were incomplete and excluded from analysis

## Agent Design & Logic

- Agent-first design: The prompt defines behavior, reasoning, and constraints
- Quiz-driven context: Uses a short habit quiz when spending data lacks clarity
- Behavior-focused analysis: Prioritizes habits and patterns over raw numbers
- Logic validation: Cross-checks insights against data to avoid contradictions
- Concise responses: Outputs are short, readable, and structured for clarity

## Constraints & Responsible AI Rules

- Does not calculate taxes or predict exact savings
- Does not give financial, investment, or tax advice
- Does not recommend specific schemes, products, or instruments
- Avoids psychology jargon and technical terminology
- Remains region-neutral unless the user specifies location or currency
- Clearly informs users when data is missing or skipped
- Educational and awareness-focused only

## Versioning

### version1

- Basic expense analysis
- Category-level spending insights

### version2

- Added habit quiz for better behavioral context
- Shorter, more precise responses
- Data transparency warnings for incomplete inputs
- Region-neutral tax-awareness logic
- Improved introduction and user guidance

## Live App Link

🔗 Gemini AI Studio (SpendAI – Live Prototype):
https://aistudio.google.com/app/prompts?state=%7B%22ids%22%3A%5B%221jN7QCDq6VjnlYZQSEsJtZWBWU7ecnyF_%22%5D%2C%22action%22%3A%22open%22%2C%22userId%22%3A%22110284030720782748661%22%2C%22resourceKeys%22%3A%7B%7D%7D

## Built With

- Gemini AI Studio
- Prompt Engineering
- Agentic AI Design
