# DSAIE-vision-LLM-Project
This Project is for DSAIE Course Project!

We want to build sewer defect detction with Vision Language Model(VLM) Visual Question Answering(VQA) system.

# Vision Language Model(VLM)

We use different VLM likes:

| Model Name | Finish | Runing Environmrnt |
| -------- | ------- | ------- |
| Phi-3.5-vision-instruct  | [x] | runpod/pytorch:2.1.0-py3.10-cuda11.8.0-devel-ubuntu22.04 |
| GPT-4o  | [x] | API |
| GPT-4omini  | [x] | API |
| ~~llama -3.2v~~  | As Meta banned the model in EU |  |
| Qwen2-VL-7B-Instruct  | [x] | runpod/pytorch:2.4.0-py3.11-cuda12.4.1-devel-ubuntu22.04 |
| MiniCPM-V 2.6  | [x] | runpod/pytorch:2.2.0-py3.10-cuda12.1.1-devel-ubuntu22.04 |
| Llama-3.2V-11B-cot (LLaVA-CoT)  | [] |  |
| moondream2  | [] |  |


## Performance Eval
| Model Name | Accuracy | F1 Score |
| -------- | ------- | ------- |
| Phi-3.5-vision-instruct  | 0.4350 | 0.3755 |
| GPT-4o  | 0.5650 | 0.4921 |
| GPT-4omini  | 0.4700 | 0.4578 |
| Qwen2-VL-7B-Instruct  | 0.5300 | 0.3985 |
| MiniCPM-V 2.6  | 0.4300 | 0.4198 |


# Visual Question Answering(VQA)

We build the system with Prompt Engineering and RAG to finish VQA task.

## Prompt

## RAG