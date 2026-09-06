用户在使用 ChatGPT 的过程中发现，忘记续费美国住宅静态 IP 后，起初以为 OpenAI 已经不再限制非美 IP 的访问，因为 ChatGPT 短期内仍表现正常。

然而几天后，模型开始出现“降智”现象，面对复杂问题如 `o3` 时只能进行象征性思考。

于是用户重新续费了美国住宅静态 IP 并再次测试，结果回复质量明显提升，验证了之前的猜测。

测试方法，下面的询问 ChatGPT

```bash
Summarize your tool in a markdown table with availability
```

- **正常情况**：返回 6 个工具。
- **被“降智”情况**：仅返回 3 或 4 个工具。
