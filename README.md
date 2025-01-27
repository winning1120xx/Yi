<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/01-ai/Yi/main/assets/img/Yi_logo_icon_dark.svg" width="200px">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/01-ai/Yi/main/assets/img/Yi_logo_icon_light.svg" width="200px"> 
  <img alt="specify theme context for images" src="https://raw.githubusercontent.com/01-ai/Yi/main/assets/img/Yi_logo_icon_light.svg" width="200px">
</picture>

</br>
</br>

<a href="https://github.com/01-ai/Yi/actions/workflows/build_docker_image.yml">
  <img src="https://github.com/01-ai/Yi/actions/workflows/build_docker_image.yml/badge.svg">
</a>
<a href="https://github.com/01-ai/Yi/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/Code_License-Apache_2.0-lightblue">
</a>
<a href="https://github.com/01-ai/Yi/blob/main/MODEL_LICENSE_AGREEMENT.txt">
  <img src="https://img.shields.io/badge/Model_License-Yi_License-lightblue">
</a>
<a href="mailto:oss@01.ai">
  <img src="https://img.shields.io/badge/✉️-yi@01.ai-FFE01B">
</a>

</div>

<div align="center">
  <h3 align="center">Building the Next Generation of Open-Source and Bilingual LLMs</h3>
</div>

<p align="center">
🤗 <a href="https://huggingface.co/01-ai" target="_blank">Hugging Face</a> • 🤖 <a href="https://www.modelscope.cn/organization/01ai/" target="_blank">ModelScope</a> • ✡️ <a href="https://wisemodel.cn/organization/01.AI" target="_blank">WiseModel</a>
</p> 

<p align="center">
    👩‍🚀 Ask questions or discuss ideas on <a href="https://github.com/01-ai/Yi/discussions" target="_blank"> GitHub </a>!
</p> 

<p align="center">
    👋 Join us on 💬 <a href="https://github.com/01-ai/Yi/issues/43#issuecomment-1827285245" target="_blank"> WeChat (Chinese) </a>!
</p> 

<p align="center">
    📚 Grow at <a href="https://github.com/01-ai/Yi/blob/main/docs/learning_hub.md"> Yi Learning Hub </a>!
</p> 


<!-- DO NOT REMOVE ME -->

<hr>

<details open>
<summary></b>📕 Table of Contents</b></summary>

- [🟢 What is Yi?](#-what-is-yi)
  - [📌 Introduction](#-introduction)
  - [🎯 Models](#-models)
    - [Chat models](#chat-models)
    - [Base models](#base-models)
    - [Other info](#other-info)
  - [🎉 News](#-news)
- [🟢 How to use Yi?](#-how-to-use-yi)
  - [Quick start](#quick-start)
    - [Choose your path](#choose-your-parth)
    - [pip](#pip)
    - [llama.cpp](https://github.com/01-ai/Yi/blob/main/docs/yi_llama.cpp.md)
    - [Web demo](#web-demo)
  - [Fine tune](#fine-tune)
  - [Quantization](#quantization)
  - [Deployment](https://github.com/01-ai/Yi/blob/main/docs/deployment.md)
  - [Learning hub](https://github.com/01-ai/Yi/blob/main/docs/learning_hub.md)
- [🟢 Why Yi?](#-why-yi)
  - [🌎 Ecosystem](#-ecosystem)
    - [💦 Upstream](#-upstream)
    - [🌊 Downstream](#-downstream)
      - [🔗 Serving](#-serving)
      - [⚙️ Quantitation](#️-quantitation)
      - [🛠️ Fine-tuning](#️-fine-tuning)
      - [API](#api)
  - [📌 Benchmarks](#-benchmarks)
    - [📊 Base model performance](#-base-model-performance)
    - [📊 Chat model performance](#-chat-model-performance)
    - [📊 Quantized chat model performance](#-quantized-chat-model-performance)
- [🟢 Who can use Yi?](#-who-can-use-yi)
- [🟢 Misc.](#-misc)
  - [Ackknowledgements](#acknowledgments)
  - [📡 Disclaimer](#-disclaimer)
  - [🪪 License](#-license)

</details>

<hr>

# 🟢 What is Yi?

## 📌 Introduction 

- 🤖 The Yi series models are the next generation of open-source large language models trained from scratch by [01.AI](https://01.ai/).

- 🙌 Targeted as a bilingual language model and trained on 3T multilingual corpus, the Yi series models become one of the strongest LLM worldwide, showing promise in language understanding, commonsense reasoning, reading comprehension, and more. For example,

  - For English language capability, the Yi series models ranked 2nd (just behind GPT-4), outperforming other LLMs (such as LLaMA2-chat-70B, Claude 2, and ChatGPT) on the [AlpacaEval Leaderboard](https://tatsu-lab.github.io/alpaca_eval/) in Dec 2023.
  
  - For Chinese language capability, the Yi series models landed in 2nd place (following GPT-4), surpassing other LLMs (such as Baidu ERNIE, Qwen, and Baichuan) on the [SuperCLUE](https://www.superclueai.com/) in Oct 2023.

- 🙏 (Credits to LLaMA) Thanks to the Transformer and LLaMA open-source communities, as they reducing the efforts required to build from scratch and enabling the utilization of the same tools within the AI ecosystem. If you're interested in Yi's adoption of LLaMA architecture and license usage policy, see [Yi's relation with LLaMA](https://github.com/01-ai/Yi/blob/main/docs/yi_relation_llama.md).

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

## 🎯 Models

Yi models come in multiple sizes and cater to different use cases. You can also fine-tune Yi models to meet your specific requirements. 

If you want to deploy Yi models, see [software and hardware requirements](https://github.com/01-ai/Yi/blob/main/docs/deployment.md#hardware-requirements).

### Chat models

| Model | Download  
|---|---
Yi-6B-Chat| • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-6B-Chat) • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-6B-Chat/summary)
Yi-6B-Chat-4bits |	• [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-6B-Chat-4bits)  • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-6B-Chat-4bits/summary)
Yi-6B-Chat-8bits	|  • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-6B-Chat-8bits) • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-6B-Chat-8bits/summary)
Yi-34B-Chat	| • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-34B-Chat)  • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-34B-Chat/summary)
Yi-34B-Chat-4bits	| • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-34B-Chat-4bits)  • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-34B-Chat-4bits/summary)
Yi-34B-Chat-8bits | • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-34B-Chat-8bits) • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-34B-Chat-8bits/summary)

<sub><sup> - 4-bit series models are quantized by AWQ. <br> - 8-bit series models are quantized by GPTQ <br> - All quantized models have a low barrier to use since they can be deployed on consumer-grade GPUs (e.g., 3090, 4090). </sup></sub>

### Base models

| Model | Download | 
|---|---|
Yi-6B| • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-6B)  • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-6B/summary)
Yi-6B-200K	| • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-6B-200K) • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-6B-200K/summary)
Yi-34B| • [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-34B)  • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-34B/summary)
Yi-34B-200K|• [🤗 Hugging Face](https://huggingface.co/01-ai/Yi-34B-200K)  • [🤖 ModelScope](https://www.modelscope.cn/models/01ai/Yi-34B-200K/summary)

<sub><sup> - 200k is roughly equivalent to 400,000 Chinese characters.  </sup></sub>

### Other info

- For chat and base models:

  - 6B series models are suitable for personal and academic use.

  - 34B series models suitable for personal, academic, and commercial (particularly for small and medium-sized enterprises) purposes. It's a cost-effective solution that's affordable and equipped with emergent ability.

  - The **default context window** is **4k tokens**.
    
  - The pretrained tokens are 3T.
    
  - The training data are up to June 2023.	

- For chat models:
  
  - For detailed chat model limitations, see [limitations of chat model](https://github.com/01-ai/Yi/blob/main/docs/README_legacy.md#limitations-of-chat-model).

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

## 🎉 News 

<details>
<summary>🎯 <b>2023/11/23</b>: The chat models are open to public.</summary>

This release contains two chat models based on previously released base models, two 8-bit models quantized by GPTQ, and two 4-bit models quantized by AWQ.

- `Yi-34B-Chat`
- `Yi-34B-Chat-4bits`
- `Yi-34B-Chat-8bits`
- `Yi-6B-Chat`
- `Yi-6B-Chat-4bits`
- `Yi-6B-Chat-8bits`

You can try some of them interactively at:

- [Hugging Face](https://huggingface.co/spaces/01-ai/Yi-34B-Chat)
- [Replicate](https://replicate.com/01-ai)
</details>

<details>
<summary>🔔 <b>2023/11/23</b>: The Yi Series Models Community License Agreement is updated to v2.1.</summary>
</details>

<details> 
<summary>🔥 <b>2023/11/08</b>: Invited test of Yi-34B chat model.</summary>

Application form:

- [English](https://cn.mikecrm.com/l91ODJf)
- [Chinese](https://cn.mikecrm.com/gnEZjiQ)

</details>

<details>
<summary>🎯 <b>2023/11/05</b>: The base model of <code>Yi-6B-200K</code> and <code>Yi-34B-200K</code>.</summary>

This release contains two base models with the same parameter sizes as the previous
release, except that the context window is extended to 200K.

</details>

<details>
<summary>🎯 <b>2023/11/02</b>: The base model of <code>Yi-6B</code> and <code>Yi-34B</code>.</summary>

The first public release contains two bilingual (English/Chinese) base models
with the parameter sizes of 6B and 34B.  Both of them are trained with 4K
sequence length and can be extended to 32K during inference time.

</details>

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

# 🟢 How to use Yi?

- [Quick start](#quick-start)
  - [Choose your path](#choose-your-parth)
  - [pip](#pip)
  - [llama.cpp](https://github.com/01-ai/Yi/blob/main/docs/yi_llama.cpp.md)
  - [Web demo](#web-demo)
- [Fine tune](#fine-tune)
- [Quantization](#quantization)
- [Deployment](https://github.com/01-ai/Yi/blob/main/docs/deployment.md)
- [Learning hub](https://github.com/01-ai/Yi/blob/main/docs/learning_hub.md)

## Quick start

Getting up and running with Yi models is simple with multiple choices available. 

### Choose your path

Select one of the following paths to begin your journey with Yi!

 ![Quick start - Choose your path](./assets/img/quick_start_path.png)

#### 🎯 Deploy Yi locally

If you prefer to deploy Yi models locally, 

  - 🙋‍♀️ and you have **sufficient** resources (for example, NVIDIA A800 80GB), you can choose one of the following methods:
    - [pip](#pip)
    - [Docker](https://github.com/01-ai/Yi/blob/main/docs/README_legacy.md#11-docker)
    - [conda-lock](https://github.com/01-ai/Yi/blob/main/docs/README_legacy.md#12-local-development-environment)

  - 🙋‍♀️ and you have **limited** resources (for example, a MacBook Pro), you can use [llama.cpp](https://github.com/01-ai/Yi/blob/main/docs/yi_llama.cpp.md).

#### 🎯 Not to deploy Yi locally

If you prefer not to deploy Yi models locally, you can explore Yi's capabilities using any of the following options.

##### 🙋‍♀️ Run Yi with APIs

If you want to explore more features of Yi, you can adopt one of these methods:

- Yi APIs (Yi official)
  - [Early access has been granted](https://x.com/01AI_Yi/status/1735728934560600536?s=20) to some applicants. Stay tuned for the next round of access!

- [Yi APIs](https://replicate.com/01-ai/yi-34b-chat/api?tab=nodejs) (Replicate)

##### 🙋‍♀️ Run Yi in playground

If you want to chat with Yi with more customizable options (e.g., system prompt, temperature, repetition penalty, etc.), you can try one of the following options:
  
  - [Yi-34B-Chat-Playground](https://platform.lingyiwanwu.com/prompt/playground) (Yi official)
    - Access is available through a whitelist. Welcome to apply (fill out a form in [English](https://cn.mikecrm.com/l91ODJf) or [Chinese](https://cn.mikecrm.com/gnEZjiQ)).
  
  - [Yi-34B-Chat-Playground](https://replicate.com/01-ai/yi-34b-chat) (Replicate) 

##### 🙋‍♀️ Chat with Yi

 If you want to chat with Yi, you can use one of these online services, which offer a similar user experience:

- [Yi-34B-Chat](https://huggingface.co/spaces/01-ai/Yi-34B-Chat) (Yi official on Hugging Face)
  - No registration is required.

- [Yi-34B-Chat](https://platform.lingyiwanwu.com/) (Yi official beta)
  - Access is available through a whitelist. Welcome to apply (fill out a form in [English](https://cn.mikecrm.com/l91ODJf) or [Chinese](https://cn.mikecrm.com/gnEZjiQ)).

### pip

This tutorial guides you through every step of running **Yi-34B-Chat locally on an A800 (80G)** and then performing inference.

#### Step 0: Prerequistes
 
- Make sure Python 3.10 or later version is installed.

- If you want to run other Yi models, see [software and hardware requirements](https://github.com/01-ai/Yi/blob/main/docs/deployment.md).

#### Step 1: Prepare your environment 

To set up the environment and install the required packages, execute the following command.

```bash
git clone https://github.com/01-ai/Yi.git
cd yi
pip install -r requirements.txt
```

#### Step 2: Download the Yi model

You can download the weights and tokenizer of Yi models from the following sources:

- [Hugging Face](https://huggingface.co/01-ai)
- [ModelScope](https://www.modelscope.cn/organization/01ai/)
- [WiseModel](https://wisemodel.cn/organization/01.AI)

#### Step 3: Perform inference

You can perform inference with Yi chat or base models as below.

##### Perform inference with Yi chat model

1. Create a file named  `quick_start.py` and copy the following content to it.

    ```python
    from transformers import AutoModelForCausalLM, AutoTokenizer

    model_path = '<your-model-path>'

    tokenizer = AutoTokenizer.from_pretrained(model_path, use_fast=False)

    # Since transformers 4.35.0, the GPT-Q/AWQ model can be loaded using AutoModelForCausalLM.
    model = AutoModelForCausalLM.from_pretrained(
        model_path,
        device_map="auto",
        torch_dtype='auto'
    ).eval()

    # Prompt content: "hi"
    messages = [
        {"role": "user", "content": "hi"}
    ]

    input_ids = tokenizer.apply_chat_template(conversation=messages, tokenize=True, add_generation_prompt=True, return_tensors='pt')
    output_ids = model.generate(input_ids.to('cuda'))
    response = tokenizer.decode(output_ids[0][input_ids.shape[1]:], skip_special_tokens=True)

    # Model response: "Hello! How can I assist you today?"
    print(response)
    ```

2. Run `quick_start.py`.

    ```bash
    python quick_start.py
    ```

    Then you can see an output similar to the one below. 🥳

    ```bash
    Hello! How can I assist you today?
    ```

##### Perform inference with Yi base model

The steps are similar to [pip - Perform inference with Yi chat model](#perform-inference-with-yi-chat-model).

You can use the existing file [`text_generation.py`](https://github.com/01-ai/Yi/tree/main/demo).

```bash
python demo/text_generation.py  --model <your-model-path>
```

Then you can see an output similar to the one below. 🥳

<details>

<summary>Output</summary>

<br>

**Prompt**: Let me tell you an interesting story about cat Tom and mouse Jerry,

**Generation**: Let me tell you an interesting story about cat Tom and mouse Jerry, which happened in my childhood. My father had a big house with two cats living inside it to kill mice. One day when I was playing at home alone, I found one of the tomcats lying on his back near our kitchen door, looking very much like he wanted something from us but couldn’t get up because there were too many people around him! He kept trying for several minutes before finally giving up...

</details>

### Docker

This tutorial guides you through every step of running **Yi-34B-Chat on an A800 GPU** locally and then performing inference.

#### Step 0: Prerequistes

- Make sure you've installed [Docker](https://docs.docker.com/engine/install/?open_in_browser=true) and [nvidia-container-toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html).

#### Step 1: Start Docker

```bash
docker run -it --gpus all \
    -v <your-model-path>: /models
    ghcr.io/01-ai/yi:latest 
```

Alternatively, you can pull the Yi Docker image from `registry.lingyiwanwu.com/ci/01-ai/yi:latest`.

#### Step 2: Perform inference

You can perform inference with Yi chat or base models as below.
   
##### Perform inference with Yi chat model

The steps are similar to [pip - Perform inference with Yi chat model](#perform-inference-with-yi-chat-model).

**Note** that the only difference is to set `model_path = '<your-model-mount-path>'` instead of `model_path = '<your-model-path>'`.

##### Perform inference with Yi base model

The steps are similar to [pip - Perform inference with Yi base model](#perform-inference-with-yi-base-model).

**Note** that the only difference is to set `--model <your-model-mount-path>'` instead of  `model <your-model-path>`.

### Run Yi with llama.cpp

If you have limited resources, you can try [llama.cpp](https://github.com/ggerganov/llama.cpp) or [ollama.cpp](https://ollama.ai/) (especially for Chinese users) to run Yi models in a few minutes locally.

For a step-by-step tutorial, see [Run Yi with llama.cpp](https://github.com/01-ai/Yi/edit/main/docs/yi_llama.cpp.md).

### Web demo

You can build a web UI demo for Yi **chat** models (note that Yi base models are not supported in this senario).

[Step 1: Prepare your environment](#step-1-prepare-your-environment). 

[Step 2: Download the Yi model](#step-2-download-the-yi-model).

Step 3. To start a web service locally, run the following command.

```bash
python demo/web_demo.py -c <your-model-path>
```

You can access the web UI by entering the address provided in the console into your browser. 

 ![Quick start - web demo](./assets/img/yi_34b_chat_web_demo.gif)

### Finetuning

```bash
bash finetune/scripts/run_sft_Yi_6b.sh
```

Once finished, you can compare the finetuned model and the base model with the following command:

```bash
bash finetune/scripts/run_eval.sh
```

For advanced usage (like fine-tuning based on your custom data), see [fine-tune code for Yi 6B and 34B](https://github.com/01-ai/Yi/tree/main/finetune).

### Quantization

#### GPT-Q
```bash
python quantization/gptq/quant_autogptq.py \
  --model /base_model                      \
  --output_dir /quantized_model            \
  --trust_remote_code
```

Once finished, you can then evaluate the resulting model as follows:

```bash
python quantization/gptq/eval_quantized_model.py \
  --model /quantized_model                       \
  --trust_remote_code
```

For a more detailed explanation, please read the [doc](https://github.com/01-ai/Yi/tree/main/quantization/gptq)

#### AWQ
```bash
python quantization/awq/quant_autoawq.py \
  --model /base_model                      \
  --output_dir /quantized_model            \
  --trust_remote_code
```

Once finished, you can then evaluate the resulting model as follows:

```bash
python quantization/awq/eval_quantized_model.py \
  --model /quantized_model                       \
  --trust_remote_code
```

For detailed explanations, see [AWQ quantization](https://github.com/01-ai/Yi/tree/main/quantization/awq).

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

# 🟢 Why Yi? 

  - [🌎 Ecosystem](#-ecosystem)
    - [💦 Upstream](#-upstream)
    - [🌊 Downstream](#-downstream)
      - [🔗 Serving](#-serving)
      - [⚙️ Quantitation](#️-quantitation)
      - [🛠️ Fine-tuning](#️-fine-tuning)
      - [API](#api)
  - [📌 Benchmarks](#-benchmarks)
    - [📊 Base model performance](#-base-model-performance)
    - [📊 Chat model performance](#-chat-model-performance)
    - [📊 Quantized chat model performance](#-quantized-chat-model-performance)
 
## 🌎 Ecosystem

Yi has a comprehensive ecosystem, offering a range of tools, services, and models to enrich your experiences and maximize productivity.

- [💦 Upstream](#-upstream)
- [🌊 Downstream](#-downstream)
  - [🔗 Serving](#-serving)
  - [⚙️ Quantitation](#️-quantitation)
  - [🛠️ Fine-tuning](#️-fine-tuning)
  - [API](#api)

### 💦 Upstream

The Yi series models follow the same model architecture as LLaMA. By choosing Yi, you can leverage existing tools, libraries, and resources within the LLaMA ecosystem, eliminating the need to create new tools and enhancing development efficiency.

For example, the Yi series models are saved in the format of the LLaMA model. You can directly use `LLaMAForCausalLM` and `LLaMATokenizer` to load the model. For more information, see [Use the chat model](#31-use-the-chat-model).

```python
from transformers import AutoModelForCausalLM, AutoTokenizer

tokenizer = AutoTokenizer.from_pretrained("01-ai/Yi-34b", use_fast=False)

model = AutoModelForCausalLM.from_pretrained("01-ai/Yi-34b", device_map="auto")
```

### 🌊 Downstream

> 💡 Tip
> 
> - Feel free to create a PR and share the fantastic work you've built using the Yi series models.
>
> - To help others quickly understand your work, it is recommended to use the format of `<model-name>: <model-intro> + <model-highlights>`.

#### 🔗 Serving 

If you want to get up with Yi in a few minutes, you can use the following services built upon Yi.

- Yi-34B-Chat: you can chat with Yi using one of the following platforms:
  - [Yi-34B-Chat | Hugging Face](https://huggingface.co/spaces/01-ai/Yi-34B-Chat)
  - [Yi-34B-Chat | Yi Platform](https://platform.lingyiwanwu.com/): **Note** that currently it's available through a whitelist. Welcome to apply (fill out a form in [English](https://cn.mikecrm.com/l91ODJf) or [Chinese](https://cn.mikecrm.com/gnEZjiQ)) and experience it firsthand!
  
- [Yi-6B-Chat (Replicate)](https://replicate.com/01-ai): you can use this model with more options by setting additional parameters and calling APIs.
  
- [ScaleLLM](https://github.com/vectorch-ai/ScaleLLM#supported-models): you can use this service to run Yi models locally with added flexibility and customization.
  
#### ⚙️ Quantitation

If you have limited computational capabilities, you can use Yi's quantized models as follows. 

These quantized models have reduced precision but offer increased efficiency, such as faster inference speed and smaller RAM usage.

- [TheBloke/Yi-34B-GPTQ](https://huggingface.co/TheBloke/Yi-34B-GPTQ) 
- [TheBloke/Yi-34B-GGUF](https://huggingface.co/TheBloke/Yi-34B-GGUF)
- [TheBloke/Yi-34B-AWQ](https://huggingface.co/TheBloke/Yi-34B-AWQ)
  
#### 🛠️ Fine-tuning

If you're seeking to explore the diverse capabilities within Yi's thriving family, you can delve into Yi's fine-tuned models as below.

- [TheBloke Models](https://huggingface.co/TheBloke): this site hosts numerous fine-tuned models derived from various LLMs including Yi. 
  
  This is not an exhaustive list for Yi, but to name a few sorted on downloads:
  - [TheBloke/dolphin-2_2-yi-34b-AWQ](https://huggingface.co/TheBloke/dolphin-2_2-yi-34b-AWQ)
  - [TheBloke/Yi-34B-Chat-AWQ](https://huggingface.co/TheBloke/Yi-34B-Chat-AWQ)
  - [TheBloke/Yi-34B-Chat-GPTQ](https://huggingface.co/TheBloke/Yi-34B-Chat-GPTQ)
  
- [SUSTech/SUS-Chat-34B](https://huggingface.co/SUSTech/SUS-Chat-34B): this model ranked first among all models below 70B and outperformed the twice larger deepseek-llm-67b-chat. You can check the result on the [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard).
  
- [OrionStarAI/OrionStar-Yi-34B-Chat-Llama](https://huggingface.co/OrionStarAI/OrionStar-Yi-34B-Chat-Llama): this model excelled beyond other models (such as GPT-4, Qwen-14B-Chat, Baichuan2-13B-Chat) in C-Eval and CMMLU evaluations on the [OpenCompass LLM Leaderboard](https://opencompass.org.cn/leaderboard-llm). 
  
- [NousResearch/Nous-Capybara-34B](https://huggingface.co/NousResearch/Nous-Capybara-34B): this model is trained with 200K context length and 3 epochs on the Capybara dataset. 

#### API

- [amazing-openai-api](https://github.com/soulteary/amazing-openai-api): this tool converts Yi model APIs into the OpenAI API format out of the box.
- [LlamaEdge](https://www.secondstate.io/articles/yi-34b/#create-an-openai-compatible-api-service-for-the-yi-34b-chat-model): this tool builds an OpenAI-compatible API server for Yi-34B-Chat using a portable Wasm (WebAssembly) file, powered by Rust.

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

## 📌 Benchmarks 

- [📊 Base model performance](#-base-model-performance)
- [📊 Chat model performance](#-chat-model-performance)
- [📊 Quantized chat model performance](#-quantized-chat-model-performance)

### 📊 Base model performance

| Model         |   MMLU   |  CMMLU   |  C-Eval  |  GAOKAO  |   BBH    | Common-sense Reasoning | Reading Comprehension | Math & Code |
| :------------ | :------: | :------: | :------: | :------: | :------: | :--------------------: | :-------------------: | :---------: |
|               |  5-shot  |  5-shot  |  5-shot  |  0-shot  | 3-shot@1 |           -            |           -           |      -      |
| LLaMA2-34B    |   62.6   |    -     |    -     |    -     |   44.1   |          69.9          |         68.0          |    26.0     |
| LLaMA2-70B    |   68.9   |   53.3   |    -     |   49.8   |   51.2   |          71.9          |         69.4          |    36.8     |
| Baichuan2-13B |   59.2   |   62.0   |   58.1   |   54.3   |   48.8   |          64.3          |         62.4          |    23.0     |
| Qwen-14B      |   66.3   |   71.0   |   72.1   |   62.5   |   53.4   |          73.3          |         72.5          |  **39.8**   |
| Skywork-13B   |   62.1   |   61.8   |   60.6   |   68.1   |   41.7   |          72.4          |         61.4          |    24.9     |
| InternLM-20B  |   62.1   |   59.0   |   58.8   |   45.5   |   52.5   |          78.3          |           -           |    30.4     |
| Aquila-34B    |   67.8   |   71.4   |   63.1   |    -     |    -     |           -            |           -           |      -      |
| Falcon-180B   |   70.4   |   58.0   |   57.8   |   59.0   |   54.0   |          77.3          |         68.8          |    34.0     |
| Yi-6B         |   63.2   |   75.5   |   72.0   |   72.2   |   42.8   |          72.3          |         68.7          |    19.8     |
| Yi-6B-200K    |   64.0   |   75.3   |   73.5   |   73.9   |   42.0   |          72.0          |         69.1          |    19.0     |
| **Yi-34B**    | **76.3** | **83.7** |   81.4   |   82.8   | **54.3** |        **80.1**        |         76.4          |    37.1     |
| Yi-34B-200K   |   76.1   |   83.6   | **81.9** | **83.4** |   52.7   |          79.7          |       **76.6**        |    36.3     |

While benchmarking open-source models, we have observed a disparity between the
results generated by our pipeline and those reported in public sources (e.g.
OpenCompass). Upon conducting a more in-depth investigation of this difference,
we have discovered that various models may employ different prompts,
post-processing strategies, and sampling techniques, potentially resulting in
significant variations in the outcomes. Our prompt and post-processing strategy
remains consistent with the original benchmark, and greedy decoding is employed
during evaluation without any post-processing for the generated content. For
scores that were not reported by the original authors (including scores reported
with different settings), we try to get results with our pipeline.

To evaluate the model's capability extensively, we adopted the methodology
outlined in Llama2. Specifically, we included PIQA, SIQA, HellaSwag, WinoGrande,
ARC, OBQA, and CSQA to assess common sense reasoning. SquAD, QuAC, and BoolQ
were incorporated to evaluate reading comprehension. CSQA was exclusively tested
using a 7-shot setup, while all other tests were conducted with a 0-shot
configuration. Additionally, we introduced GSM8K (8-shot@1), MATH (4-shot@1),
HumanEval (0-shot@1), and MBPP (3-shot@1) under the category "Math & Code". Due
to technical constraints, we did not test Falcon-180 on QuAC and OBQA; the score
is derived by averaging the scores on the remaining tasks. Since the scores for
these two tasks are generally lower than the average, we believe that
Falcon-180B's performance was not underestimated.

### 📊 Chat model performance

| Model                   | MMLU      | MMLU      | CMMLU     | CMMLU     | C-Eval(val)<sup>*</sup> | C-Eval(val)<sup>*</sup> | Truthful QA | BBH       | BBH       | GSM8k     | GSM8k     |
| ----------------------- | --------- | --------- | --------- | --------- | ----------------------- | ----------------------- | ----------- | --------- | --------- | --------- | --------- |
|                         | 0-shot    | 5-shot    | 0-shot    | 5-shot    | 0-shot                  | 5-shot                  | 0-shot      | 0-shot    | 3-shot    | 0-shot    | 4-shot    |
| LLaMA2-13B-Chat         | 50.88     | 47.33     | 27.47     | 35.08     | 27.93                   | 35.88                   | 36.84       | 32.90     | 58.22     | 36.85     | 2.73      |
| LLaMA2-70B-Chat         | 59.42     | 59.86     | 36.10     | 40.99     | 34.99                   | 41.31                   | 53.95       | 42.36     | 58.53     | 47.08     | 58.68     |
| Baichuan2-13B-Chat      | 55.09     | 50.14     | 58.64     | 59.47     | 56.02                   | 54.75                   | 48.98       | 38.81     | 47.15     | 45.72     | 23.28     |
| Qwen-14B-Chat           | 63.99     | 64.98     | 67.73     | 70.57     | 66.12                   | 70.06                   | 52.49       | 49.65     | 54.98     | 59.51     | 61.18     |
| InternLM-Chat-20B       | 55.55     | 57.42     | 53.55     | 53.75     | 51.19                   | 53.57                   | 51.75       | 42.41     | 36.68     | 15.69     | 43.44     |
| AquilaChat2-34B v1.2    | 65.15     | 66.70     | 67.51     | 70.02     | **82.99**               | **89.38**               | **64.33**   | 20.12     | 34.28     | 11.52     | 48.45     |
| Yi-6B-Chat              | 58.24     | 60.99     | 69.44     | 74.71     | 68.80                   | 74.22                   | 50.58       | 39.70     | 47.15     | 38.44     | 44.88     |
| Yi-6B-Chat-8bits(GPTQ)  | 58.29     | 60.96     | 69.21     | 74.69     | 69.17                   | 73.85                   | 49.85       | 40.35     | 47.26     | 39.42     | 44.88     |
| Yi-6B-Chat-4bits(AWQ)   | 56.78     | 59.89     | 67.70     | 73.29     | 67.53                   | 72.29                   | 50.29       | 37.74     | 43.62     | 35.71     | 38.36     |
| Yi-34B-Chat             | **67.62** | 73.46     | **79.11** | **81.34** | 77.04                   | 78.53                   | 62.43       | 51.41     | **71.74** | **71.65** | **75.97** |
| Yi-34B-Chat-8bits(GPTQ) | 66.24     | **73.69** | 79.05     | 81.23     | 76.82                   | 78.97                   | 61.84       | **52.08** | 70.97     | 70.74     | 75.74     |
| Yi-34B-Chat-4bits(AWQ)  | 65.77     | 72.42     | 78.21     | 80.50     | 75.71                   | 77.27                   | 61.84       | 48.30     | 69.39     | 70.51     | 74.00     |

We evaluated various benchmarks using both zero-shot and few-shot methods, except for TruthfulQA. Generally, the zero-shot approach is more common in chat models. Our evaluation strategy involves generating responses while following instructions explicitly or implicitly (such as using few-shot examples). We then isolate relevant answers from the generated text. Some models are not well-suited to produce output in the specific format required by instructions in a few datasets, which leads to suboptimal results. 

<strong>*</strong>: C-Eval results are evaluated on the validation datasets

### 📊 Quantized chat model performance

We also provide both 4-bit (AWQ) and 8-bit (GPTQ) quantized Yi chat models. Evaluation results on various benchmarks have shown that the quantized models have **negligible** losses. Additionally, they reduce the memory footprint size. 

# 🟢 Who can use Yi?

Everyone! 🙌 ✅

- The Yi series models are free for personal usage, academic purposes, and commercial use. All usage must adhere to the [Yi Series Models Community License Agreement 2.1](https://github.com/01-ai/Yi/blob/main/MODEL_LICENSE_AGREEMENT.txt)
  
- For free commercial use, you only need to [complete this form](https://www.lingyiwanwu.com/yi-license) to get a Yi Model Commercial License.

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

# 🟢 Misc.

### Acknowledgments

A heartfelt thank you to each of you who have made contributions to the Yi community! You have helped Yi not just a project, but a vibrant, growing home for innovation.

<!---
ref https://github.com/ngryman/contributor-faces
npx contributor-faces --exclude "*bot*" --limit 70 --repo "https://github.com/01-ai/Yi"

change the height and width for each of the contributors from 80 to 50 at ref index.js.
--->

[//]: contributor-faces
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/ZhaoFancy"><img style="margin:0" src="https://avatars.githubusercontent.com/u/139539780?v=4" title="ZhaoFancy" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/Anonymitaet"><img style="margin:0" src="https://avatars.githubusercontent.com/u/50226895?v=4" title="Anonymitaet" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/findmyway"><img style="margin:0" src="https://avatars.githubusercontent.com/u/5612003?v=4" title="findmyway" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/shiyue-loop"><img style="margin:0" src="https://avatars.githubusercontent.com/u/150643331?v=4" title="shiyue-loop" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/richardllin"><img style="margin:0" src="https://avatars.githubusercontent.com/u/1932744?v=4" title="richardllin" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/jiangchengSilent"><img style="margin:0" src="https://avatars.githubusercontent.com/u/143983063?v=4" title="jiangchengSilent" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/loofahcus"><img style="margin:0" src="https://avatars.githubusercontent.com/u/15729967?v=4" title="loofahcus" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/Yimi81"><img style="margin:0" src="https://avatars.githubusercontent.com/u/66633207?v=4" title="Yimi81" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/ly-nld"><img style="margin:0" src="https://avatars.githubusercontent.com/u/38471793?v=4" title="ly-nld" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/WayTooWill"><img style="margin:0" src="https://avatars.githubusercontent.com/u/119883899?v=4" title="WayTooWill" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/kai01ai"><img style="margin:0" src="https://avatars.githubusercontent.com/u/140378742?v=4" title="kai01ai" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/forpanyang"><img style="margin:0" src="https://avatars.githubusercontent.com/u/138085590?v=4" title="forpanyang" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/0x1111"><img style="margin:0" src="https://avatars.githubusercontent.com/u/750392?v=4" title="0x1111" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/angeligareta"><img style="margin:0" src="https://avatars.githubusercontent.com/u/32129522?v=4" title="angeligareta" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/xffxff"><img style="margin:0" src="https://avatars.githubusercontent.com/u/30254428?v=4" title="xffxff" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/tpoisonooo"><img style="margin:0" src="https://avatars.githubusercontent.com/u/7872421?v=4" title="tpoisonooo" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/tdolan21"><img style="margin:0" src="https://avatars.githubusercontent.com/u/40906019?v=4" title="tdolan21" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/statelesshz"><img style="margin:0" src="https://avatars.githubusercontent.com/u/28150734?v=4" title="statelesshz" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/renxiaoyi"><img style="margin:0" src="https://avatars.githubusercontent.com/u/10918916?v=4" title="renxiaoyi" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/markli404"><img style="margin:0" src="https://avatars.githubusercontent.com/u/116385770?v=4" title="markli404" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/fecet"><img style="margin:0" src="https://avatars.githubusercontent.com/u/41792945?v=4" title="fecet" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/cArlIcon"><img style="margin:0" src="https://avatars.githubusercontent.com/u/7384654?v=4" title="cArlIcon" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/alabulei1"><img style="margin:0" src="https://avatars.githubusercontent.com/u/45785633?v=4" title="alabulei1" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/eltociear"><img style="margin:0" src="https://avatars.githubusercontent.com/u/22633385?v=4" title="eltociear" width="50" height="50"></a>
<a style="display:inline-block;width=50px;height=50px" href="https://github.com/Gmgge"><img style="margin:0" src="https://avatars.githubusercontent.com/u/48548141?v=4" title="Gmgge" width="50" height="50"></a>

[//]: contributor-faces

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

### 📡 Disclaimer

We use data compliance checking algorithms during the training process, to
ensure the compliance of the trained model to the best of our ability. Due to
complex data and the diversity of language model usage scenarios, we cannot
guarantee that the model will generate correct, and reasonable output in all
scenarios. Please be aware that there is still a risk of the model producing
problematic outputs. We will not be responsible for any risks and issues
resulting from misuse, misguidance, illegal usage, and related misinformation,
as well as any associated data security concerns.

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>

### 🪪 License

The source code in this repo is licensed under the [Apache 2.0
license](https://github.com/01-ai/Yi/blob/main/LICENSE). The Yi series models
are fully open for academic research and free commercial usage with permission
via applications. All usage must adhere to the [Yi Series Models Community License Agreement 2.1](https://github.com/01-ai/Yi/blob/main/MODEL_LICENSE_AGREEMENT.txt).
For free commercial use, you only need to send an email to [get official commercial permission](https://www.lingyiwanwu.com/yi-license).

<div align="right"> [ <a href="#building-the-next-generation-of-open-source-and-bilingual-llms">Back to top ⬆️ </a> ] </div>
