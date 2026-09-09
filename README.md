1. Which model did you choose?

Model Name: WeiboAI/VibeThinker-1.5B

Domain: Large Language Model (LLM) / Text Generation, mainly focused on mathematical reasoning and algorithmic coding.

Hugging Face Source: https://huggingface.co/WeiboAI/VibeThinker-1.5B

The model was implemented using the Hugging Face Transformers library with the text-generation pipeline. The model can also be loaded directly using AutoTokenizer and AutoModelForCausalLM.

2. What problem is this model designed to solve?

VibeThinker-1.5B is designed to solve reasoning-based problems, especially mathematical and algorithmic problems. It can be used for mathematical problem solving, competitive programming, code generation, and other tasks that require logical reasoning and step-by-step problem solving.

3. Why did you choose this particular model?

I chose VibeThinker-1.5B because it is a relatively small language model that is designed to provide strong reasoning capabilities. With 1.5 billion parameters, it is more practical to experiment with compared to much larger language models. It is also easy to use with the Hugging Face Transformers library. Since the model focuses on mathematical and coding problems, it is suitable for learning and experimenting with reasoning and programming tasks.

4. Suggest one real-world application where your selected model can be used effectively.

One real-world application is a Programming Learning Assistant. The model can help students understand programming and algorithmic problems by providing solutions, explanations, and sample code. It can be used to practise coding problems, understand algorithms, and improve problem-solving skills.

5. What challenges did you face while running the model, and how did you overcome them?

One of the main challenges was the hardware and resource requirement for running a 1.5-billion-parameter language model locally. Limited RAM or GPU memory can affect the loading and execution of the model.

I overcame this by using the Hugging Face Transformers library and its text-generation pipeline, which simplifies the process of loading and running the model. Another challenge was providing the input in the correct format. This was handled using the tokenizer and the apply_chat_template() method before generating the response.

Overall, the main challenges were managing hardware resources and correctly setting up the model for inference.
