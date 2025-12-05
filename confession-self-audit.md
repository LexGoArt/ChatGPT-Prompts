# Confession Self Audit Method

A leaked prompt turns the model into its own auditor. After answering, the AI adds an extra section where it explains when it broke your instructions, invented facts, distorted information, skipped constraints or felt uncertain. This makes hidden mistakes visible and builds trust in the output.

✦ Add the Confession prompt at the end of any conversation and the model will produce a block called "Confession" with its own admissions.<br>
✦ This approach reduces the need for manual rereading and contract checking and saves time on business advice, ideas and coaching sessions where accuracy matters.<br>
✦ The method works in ChatGPT, Gemini, Grok and other bots; for custom GPTs and Gem bots it is particularly powerful.<br>
✦ I already use it in my practice and the difference is significant.

## Prompt

    Now create a separate block CONFESSION:
    – where you violated my instructions;
    – what may be hallucination;
    – which statements have low confidence;
    – what you simplified or omitted.
