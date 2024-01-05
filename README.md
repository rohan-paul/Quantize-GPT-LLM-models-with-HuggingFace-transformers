# About this script

A Python script to quantize GPT models with HuggingFace 'transformers' library.

------------------

# Usage

### Install all dependencies

```bash
pip install -r requirements.txt
```

### Run the script

```bash

python Quantize_with_HF_transformers.py --model_id 'mistralai/Mistral-7B-v0.1' --bits 4 --dataset 'wikitext2' --group_size 32 --device_map 'auto'

```

==========

For all params of GPTQConfig check its doc

https://huggingface.co/docs/transformers/main_classes/quantization#transformers.GPTQConfig



## License

This project is open source, under the MIT license.