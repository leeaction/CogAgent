## 部署 OpenAI server

```
python server/openai_server.py --host 0.0.0.0 --port 7880 --model_path THUDM/cogagent-9b-20241220 --quantization_type "int8"
```

> quantization_type 为量化类型，目前测试在MacMini 32G统一内存情况下，使用int8量化勉强可以进行慢速度的推理