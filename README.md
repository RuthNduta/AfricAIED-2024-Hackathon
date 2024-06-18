# AfricAIED-2024-Hackathon
Submission for a Biology Learning assistant


For the hackathon, we will fine-tune Microsoft's Phi-2 relatively small 2.7B model - which has "showcased a nearly state-of-the-art performance among models with less than 13 billion parameters" - on Biology questions cleaned and preprocessed from the NMSQ dataset for all years since 2019.

Here we will use QLoRA (Efficient Finetuning of Quantized LLMs), a highly efficient fine-tuning technique that involves quantizing a pre trained LLM to just 4 bits and adding small “Low-Rank Adapters”. This unique approach allows for fine-tuning LLMs using just a single GPU! This technique is supported by the PEFT library.

We are building a biology virtual assistant to help kids learn and prepare for the NSMQ especially those with scarce resource and learning disabilities.
