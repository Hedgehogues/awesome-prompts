# awesome-prompts
This repository contains a diverse collection of prompts designed for various tasks, from language learning to problem-solving and more. Each prompt follows a structured approach to ensure clarity and facilitate step-by-step reasoning

# Purpose
The prompts in this repository are intended to guide users through specific tasks by providing detailed instructions and logical frameworks. These tasks cover a broad range of topics, including but not limited to:

- Language translation and analysis
- Technical problem-solving
- Educational exercises
- Creative thought processes
- Etc...

# Key Approaches
For high-quality prompt writing, the repository emphasizes the importance of using structured methodologies such as:
- **SMART goal-setting**. Ensuring that each prompt is Specific, Measurable, Achievable, Relevant, and Time-bound
- **Systems Thinking & Design**. Utilizing the concepts of systems, supersystems, supply chains, and system transitions to provide a holistic approach to problem-solving

# Structure
Each prompt typically includes the following elements:
- Model parameters. Model parameters are the settings that control the behavior and output of a language model. They influence how the model generates text, balancing creativity, coherence, and relevance
- Context. A brief introduction to the task
- Task. Specific instructions for completing the task
- Format. Instructions for format of response
- Instructions. A detailed breakdown of how to approach the problem, encouraging systematic thinking
- Algorithm. A step-by-step guide to solving the task efficiently
- Math definition problems like [this](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/thai-word-visualisation.pmt)

# Features
- User Interaction section: Demonstrates effective engagement with users, enhancing the overall experience, [example](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/paper.pmt)
- New Variable Type <TEXT_LANGUAGE>: Reduces model errors by providing clearer context for language-specific content, [example](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/paper.pmt)
- Text Format Section: Updated from "Instructions" to "Text Format" for improved clarity, [example](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/paper.pmt)
- Section Format: Introduces "Section Format" to guide how to structure information effectively, [example](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/paper.pmt)
- Sequential Structure: Replaces "Section Structure" with "Sequence" to enhance communication and clarify steps in the process, [example](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/paper.pmt)

## Model's parameters

[Example](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/developer-grades.pmt)

### top_p
This parameter controls probabilistic sampling. When setting `top_p` (also known as "nucleus sampling"), the model will choose from a range of tokens whose cumulative probability equals `top_p`. For example, if `top_p = 0.9`, the model will select only from tokens that collectively have a 90% probability. This helps maintain diversity and creativity in responses.

### temperature
This parameter determines the level of randomness in the model's responses. A temperature value below 1 (e.g., 0.5) makes responses more predictable and less diverse, while values above 1 (e.g., 1.5) increase creativity and diversity but may lead to less coherent responses.

### frequency_penalty
This parameter is applied to reduce the likelihood of repeating the same tokens in a response. Values range from 0 to 2, where higher values decrease the probability of repetitions. This is useful for creating more varied responses.

### presence_penalty
This parameter penalizes tokens that are already present in the text, thereby reducing the likelihood of reusing the same words or phrases. This helps avoid repetition and makes the text more diverse.

### maximum_length
This parameter limits the maximum number of tokens in a response. Setting a limit helps control the length of responses, which is especially important for specific tasks that require brevity.

# ChatGPT plugins
- RnD plugin for techs, [plugin](https://chatgpt.com/g/g-Z5ySJnoPT-generatsiia-postov-pro-tekhnologii), [prompt](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/rnd-tech.pmt)
- Thai translator, [plugin](https://chatgpt.com/g/g-Xqyu6QRrj-thai-language), [prompt](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/thai-translator.pmt)
- Thai image differencer, [plugin](https://chatgpt.com/g/g-ZnOEtt5Am-words-differences), [prompt](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/word-visualisation.pmt), [example](https://chatgpt.com/share/66f1c802-c888-8003-ab49-3862a0dba03a)
- Developer's grades [prompt](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/developer-grades.pmt)
- Structure scientific paper [plugin](https://chatgpt.com/g/g-qA7hpxKes-razbor-nauchnoi-stati), [prompt](https://github.com/Hedgehogues/awesome-prompts/blob/main/promts/paper.pmt)
