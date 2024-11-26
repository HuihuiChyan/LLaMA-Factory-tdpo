## Token-level DPO

This is the adapted version of [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) which support token-level DPO.

Please format your preference data in alpaca style, refering to the example of ./data/tdpo_demo.json

Please refer to the yaml file ./examples/train_lora/llama3_lora_tdpo.yaml to format your setting file.

For token-level dpo training, you can run the following script:
```bash
llamafactory-cli train examples/train_lora/llama3_lora_tdpo.yaml
```

For any questions, please sent 5RMB to this AliPay account: 2745481838@qq.com and I will answer any of your questions.