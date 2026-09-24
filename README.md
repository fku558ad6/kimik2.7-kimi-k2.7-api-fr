# Kimi K2.7 Guide API（kimi-k2.7 / kimik2.7）

> À l'usage, rechargement dès 1 $, endpoint compatible OpenAI. **input $0.7429; output $3.083**

**[模型页](https://go.apimart.ai/k-e88cd1) · [实时价格](https://go.apimart.ai/k-2199f9) · [获取 API Key](https://go.apimart.ai/k-0a9053)**

## Tarifs（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `input` | $0.7429 |
| `output` | $3.083 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"kimi-k2.7-code","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

Ce dépôt documente l'accès via APIMart, passerelle tierce.
