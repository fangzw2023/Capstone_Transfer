For the model downloading, please help to download the below models: 

## For llamacpp:
https://github.com/ggerganov/llama.cpp (need to download github file, cannot use git clone in uob computer)

## CodeLlama:
Option1 (baseline benchmark):https://huggingface.co/Qwen/CodeQwen1.5-7B-Chat-GGUF (Top in the code generation list with smallest model size) codeqwen-1_5-7b-chat-q5_k_m.gguf

Option2 (for checking on sql code): https://huggingface.co/TheBloke/sqlcoder-7B-GGUF/tree/main sqlcoder-7b.Q5_K_M.gguf
Option3 (from a more reliable source -Meta with similar performance but considerable larger size): https://huggingface.co/TheBloke/CodeLlama-34B-Instruct-GGUF/tree/main (codellama-34b-instruct.Q4_K_M.gguf)

Option 4 (GPTQ version of CodeLlama-34B to compare the performance of GGUF and GPTQ) https://huggingface.co/TheBloke/CodeLlama-34B-Instruct-GPTQ/tree/main (all files under the link)


## For llama3 instruct:
Option1(baseline benchmark): https://huggingface.co/QuantFactory/Meta-Llama-3-8B-Instruct-GGUF/tree/main (Meta-Llama-3-8B-Instruct.Q4_K_M.gguf)
Option2(to test on model improvement) https://huggingface.co/TheBloke/Mixtral-8x7B-Instruct-v0.1-GGUF/tree/main mixtral-8x7b-instruct-v0.1.Q4_K_M.gguf
