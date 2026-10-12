# Crazyrouter API pricing reference

Snapshot: 2026-10-12, default account group, USD per million tokens. Source: [public pricing API](https://crazyrouter.com/api/pricing). Check the [current pricing page](https://crazyrouter.com/en/pricing) before purchasing.

| Model ID | Input / 1M | Output / 1M |
|---|---:|---:|
| `gpt-4o-mini` | $0.0975 | $0.39 |
| `gpt-4o` | $1.625 | $6.5 |
| `claude-sonnet-4-6` | $1.95 | $9.75 |
| `claude-opus-4-6` | $3.25 | $16.25 |
| `gemini-2.5-pro` | $0.6875 | $5.5 |
| `gemini-2.5-flash` | $0.165 | $1.375 |

These are basic uncached input/output rates. Long-context tiers, cache creation/reads, tools, audio, images, video, taxes and account-specific groups can change the bill. There is no universal percentage discount across all models.

## Estimate a workload

For a text-only workload at the displayed tier:

`cost = input_tokens / 1_000_000 * input_rate + output_tokens / 1_000_000 * output_rate`

For example, 1 million uncached input tokens and 200,000 output tokens on `gpt-4o` at this snapshot cost `$1.625 + 0.2 × $6.50 = $2.925`, before other billable items.

## Comparing providers

Compare the same exact model, context tier, cache policy, billing unit and region. Provider list prices, subscriptions, batch prices and gateway account rates are different products. Missing prices must not be treated as zero.

The earlier February 2026 comparison table, flat discounts, estimated task savings and free-credit promises have been retired. This page does not claim a universal cheapest provider or unverified sign-up bonus.

[Cost calculator](https://xujfcn.github.io/crazyrouter-tools/github/pricing-calculator/) · [Model catalogue](https://crazyrouter.com/en/models) · [API documentation](https://docs.crazyrouter.com)
