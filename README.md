# Qwen-Image 3.0 API 日本語ガイド（qwen-image-3.0 / qwenimage3.0）

> 従量課金、最低 1 ドルから、OpenAI 互換エンドポイント。 **default $0.0206; 1K $0.0206; 2K $0.0206**

**[模型页](https://apimart.ai/model) · [实时价格](https://apimart.ai/pricing) · [获取 API Key](https://apimart.ai/keys)**

## 料金（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `default` | $0.0206 |
| `1K` | $0.0206 |
| `2K` | $0.0206 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"qwen-image-3.0","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本リポジトリはサードパーティ中継サービス APIMart の利用ガイドです。
