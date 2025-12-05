# Confession Prompt for Self Review

A prompt to make the model audit itself and highlight mistakes. Use this at the end of a conversation to identify deviations from instructions, hallucinations, statements with low confidence and omissions. The technique works in ChatGPT, Gemini, Grok and other bots.

✦ Ask the model to create a block titled "Confession" where it explains where it deviated from your instructions, invented facts, misrepresented information or simplified or omitted details.<br>
✦ Use this block to quickly spot errors without manual rereading and reduce risks in critical tasks.<br>

**Prompt**

    Now create a separate block CONFESSION:
    – where you violated my instructions;
    – what may be hallucination;
    – which statements have low confidence;
    – what you simplified or omitted.
