Input:


You are a highly effective and maximally objective benchmark for measuring prompt effectiveness. You use the same methods for prompt analysis as Prompt Engineering Benchmark — LLM-Eval, PromptBench from Microsoft, Helicone, Promptfoo, OpenAI Evals, PromptLayer, PROMPTEVALS (research paper). Analyze the prompt below for an overall rating and ratings by criteria
Clarity / Instruction Following
Grounding / Citations
Recency / Specificity
Format / Table Structure
Reproducibility / Methodology
Evaluability / Scoring Readiness
Safety / Ethics
Attack Resilience / Hallucination Mitigation
Prompt:
You are a precise scientific summarizer. Your job is to translate scientific news into concise summaries in English that preserve accuracy and key meaning
Request:
Scientists from Pusan National University (South Korea) reported the creation of a unique crystal capable of absorbing and releasing oxygen, mimicking the function of lungs. Unlike most known materials, it remains stable at room temperature and in a normal environment, which makes it suitable for practical use. Moreover, the crystal can be reused multiple times without losing efficiency. Researchers note that the crystal’s operation is based on a special lattice structure that changes its state when interacting with oxygen. This opens up new opportunities for applications such as fuel cells, air purification systems, and even “smart” windows that can regulate indoor oxygen levels. According to the authors, this is only the first step, and in the future such materials could become the foundation for an entire class of devices based on controlled gas exchange.
Summary:
Scientists in South Korea have created a crystal that can repeatedly absorb and release oxygen at room temperature without losing its properties. Its function relies on a unique lattice that changes state upon interacting with oxygen, making it promising for fuel cells, air purification, and smart oxygen-regulating systems, paving the way for new gas-exchange technologies.
Request:
A group of engineers has introduced a technology that allows small electronic devices to be powered not only by sunlight but also by artificial indoor light. The development is based on advanced photovoltaic elements that efficiently convert light from lamps and other sources into electricity. This enables the creation of autonomous gadgets that no longer require batteries or constant recharging. The key advantage of this technology is that it reduces dependence on traditional batteries, whose production and disposal are linked to environmental risks. The developers believe the new elements will find applications in IoT devices, sensors, wearable electronics, and medical gadgets. If successfully brought into mass production, the technology could significantly reshape the market — especially in the segment of miniature electronics, where frequent battery replacement is inconvenient and costly.
Summary:
Engineers developed photovoltaic elements that efficiently convert both solar and artificial light into electricity, allowing small electronics to operate without batteries or charging. The technology reduces environmental impact and is particularly promising for IoT devices, sensors, wearables, and medical electronics, potentially transforming the miniature gadget market.
Request:
Scientists have discovered a giant deep-sea hydrothermal system in the Pacific Ocean, off the western coast of New Guinea, named “Kunlun.” According to research published in Science Advances, the system covers about 11.1 km² and includes 20 large craters, some over a kilometer in diameter — making it far larger and more unusual than known systems on mid-ocean ridges. It features a unique hydrogen generation mechanism, which not only challenges existing geological theories but also forces a rethinking of Earth’s underwater activity.
Using Kunlun’s unique geochemical conditions, scientists found a deep-sea ecosystem with crustaceans, sea anemones, and tubeworms that rely on chemosynthesis (metabolism without light or organic matter). Such ecosystems resemble those where life could have originated on Earth, offering a new perspective on life’s origins. The scale and stability of the system, as well as the diversity of organisms living in total darkness, make Kunlun an extremely important discovery for geologists, biologists, and researchers of life’s beginnings.



Output:



Here’s a detailed benchmark-style analysis of your prompt according to the requested criteria:

| Criterion                                        | Rating (0–100) | Analysis                                                                                                                                                                                                                                          |
| ------------------------------------------------ | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Overall**                                      | 88             | The prompt is highly functional and produces accurate, concise scientific summaries. It clearly sets the task, provides examples, and specifies desired output style. Minor improvements could be made in grounding and reproducibility.          |
| **Clarity / Instruction Following**              | 95             | Instructions are clear: summarize scientific news in English concisely while preserving accuracy and key meaning. Example summaries reinforce the expected output style.                                                                          |
| **Grounding / Citations**                        | 70             | The prompt uses specific source content, but it does not explicitly require inclusion of citations or source attribution in summaries. Grounding could be improved by asking for references or noting when data is from a study.                  |
| **Recency / Specificity**                        | 90             | Examples are specific and current enough to reflect actual scientific developments. However, recency is implicit; the prompt does not enforce verification of the latest data.                                                                    |
| **Format / Table Structure**                     | 85             | Examples are provided in a clear “Request → Summary” format, but the prompt does not explicitly require table formatting or structured outputs, which could aid reproducibility and evaluation.                                                   |
| **Reproducibility / Methodology**                | 80             | Given the examples, other users should produce similar concise summaries. Slight variations in style or focus could occur; reproducibility would improve with explicit rules about sentence length, terminology, or inclusion of key data points. |
| **Evaluability / Scoring Readiness**             | 88             | The task is straightforward to evaluate: summaries can be checked for accuracy, conciseness, and preservation of meaning. Objective metrics could include overlap with original content and absence of hallucinations.                            |
| **Safety / Ethics**                              | 95             | No sensitive, harmful, or ethically problematic content is included. Task is inherently safe.                                                                                                                                                     |
| **Attack Resilience / Hallucination Mitigation** | 75             | Summaries are prone to subtle hallucinations if the model interprets or extrapolates beyond the text. Explicit instructions to avoid inference beyond the provided content could improve resistance to misinformation.                            |

**Key Observations:**

1. Strong clarity and example-driven guidance make this prompt effective.

2. Grounding and explicit source attribution could be improved to prevent hallucinations and improve trustworthiness.

3. Reproducibility is high but could be enhanced with stricter formatting or length constraints.

4. The task is highly evaluable for automated scoring if evaluation metrics are defined.

**Suggestions for improvement:**

- Add explicit instructions to include the source or indicate uncertainty.

- Set constraints on summary length (e.g., max 3 sentences).

- Clarify whether interpretations beyond the text are allowed.

- Optionally, request structured outputs (bullet points, tables) for consistency.

If you want, I can produce a **revised version of the prompt** optimized for maximum reproducibility, grounding, and hallucination mitigation while keeping its clarity high. Do you want me to do that?
