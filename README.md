# PA Appeal Prompt

A one-shot AI prompt for drafting prior authorization appeal letters. Paste it into any AI tool, add your de-identified patient data, and get a structured, evidence-mapped appeal letter back.

Click on [PA-Appeal-Prompt.txt](https://github.com/psufka/PA-Appeal-Prompt/blob/main/PA-Appeal-Prompt.txt) to access the current version of this prompt.

**To use:**

1. Copy the entire prompt
2. Paste it into your AI tool of choice (ChatGPT, Claude, Gemini, etc.)
3. Replace `[paste or dictate patient-specific information here]` with your de-identified patient data
4. Review the output — verify every date, dose, lab value, and citation against the actual chart before submitting

**Important:** Always de-identify patient data before using any AI tool that is not a HIPAA-eligible enterprise environment.

**What the prompt does:**

- Maps every clinical claim to supporting evidence in the same sentence
- Flags missing data with `[NEED DATA]` markers instead of fabricating
- Searches for the insurer's own medical policy (if the AI tool has web access)
- Builds a Coverage Criteria Mapping section for easy reviewer approval
- Includes a risk-of-delay statement
- Works for any specialty — falls back to published evidence when formal guidelines don't exist

Read the full workflow: [How I Use AI to Appeal Prior Authorization Denials](https://superintelligentmedicine.substack.com/) *(link updated after publication)*

Feel free to edit and redistribute, as per standard [MIT License](https://github.com/psufka/PA-Appeal-Prompt/blob/main/LICENSE).
