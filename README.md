# local_llm

## Stack
|tool|purpose|install|run|port|
|-|-|-|-|-|
|unsloth|run local llm|curl -fsSL https://unsloth.ai/install.sh sh|unsloth studio|http://127.0.0.1:8888|
|deepseek harness|agentic harness|git clone https://github.com/deepseek-ai/deepseek-harness.git|pnpm dsh web|http://127.0.0.1:3080|

## Install

## Run
```
cd /mnt/data/AI/deepseek-harness
pnpm dsh web

unsloth studio
```

## Parameters
### AMD Ryzen AI 9 HX 370
|parameter|value|
|-|-|
|RAM|8GB|
|VRAM|24GB|
#### Qwen3.8-27B
Source: https://huggingface.co/Qwen/Qwen3.8-27B
##### unsloth
modelhub > model > settings
|parameter|value|
|-|-|
|Context Length|194560|
|KV Cache Dtype|q8_0|
|Vision|off|
##### deepseek harness
settings > models > capacities
|parameter|value|
|-|-|
|Context window|190K|
|Max output tokens|32K|
