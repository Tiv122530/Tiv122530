<!--
README Styling Guide:
- 余計な外部リクエストが多いと読み込みが重くなるので必要に応じてコメントアウトして調整してください。
- SVGバナーやアニメーションは自作して差し替え可能です。
-->

<p align="center">
  <!-- Hero Banner (差し替え推奨) -->
  <img src="https://capsule-render.vercel.app/api?type=wave&color=0:4f46e5,100:9333ea&height=190&section=header&text=HTMLTiv&fontColor=ffffff&fontSize=60&animation=fadeIn&fontAlignY=35" alt="header" />
</p>

<p align="center">
  <img 
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2500&pause=900&repeat=true&color=8B5CF6&center=true&vCenter=true&width=600&height=50&lines=%F0%9F%91%8B+Student+Engineer;Discord+Bots+%2B+Next.js+%2B+APIs;Build+%E2%86%92+Ship+%E2%86%92+Learn+%E2%86%92+Repeat" 
    alt="Typing SVG" />
</p>

<p align="center">
  <strong>学生エンジニア / Discord Bot / Web & API / Next.js</strong><br/>
  <em>Ship fast. Learn faster.</em>
</p>

<p align="center">
  <a href="https://github.com/HTMLTiv">
    <img src="https://komarev.com/ghpvc/?username=HTMLTiv&style=flat&color=8b5cf6" alt="views" />
  </a>
  <a href="https://github.com/HTMLTiv?tab=followers">
    <img src="https://img.shields.io/github/followers/HTMLTiv?style=flat&label=Followers&color=6366f1" />
  </a>
  <img src="https://img.shields.io/badge/Status-Open%20for%20Work-10b981?style=flat&logo=rocket" />
</p>

---

## 🪄 About

> 2006年1月26日生。主にPythonを使用し、LLM（Large Language Models）にも触れています。自宅サーバー（Proxmox VE）でインフラを管理し、仮想マシン・LXCコンテナ・ストレージ・ネットワークを運用しています。サーバサイドからフロント、Bot、オートメーションまで。

| Key | Value |
|-----|-------|
| 主軸 | Python / LLM / Discord Bot / API連携 / Webフルスタック |
| 得意 | 素早いプロトタイプ → 計測 → 改善 |
| スタイル | シンプルなコア + モジュール化 + 自動化 |
| 連絡 | muzui122530@gmail.com |
| 発信 |  GitHub |
| モットー | Build → Ship → Learn → Iterate |

---

## 🧰 Tech Stack

### Core Languages
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?logo=ruby&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?logo=gnu-bash&logoColor=white)

### Frameworks & Runtime
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-0d87c9?logo=react&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-D30001?logo=rubyonrails&logoColor=white)
![Express](https://img.shields.io/badge/Express-444?logo=express&logoColor=white)
![Discord.js](https://img.shields.io/badge/discord.js-5865F2?logo=discord&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)

### Infra / Data / Ops
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-111111?logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D15?logo=railway&logoColor=white)

### Tooling / Design
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-0AC97F?logo=figma&logoColor=white)
![OBS](https://img.shields.io/badge/OBS-302E31?logo=obsstudio&logoColor=white)

---

## 🔭 Focus Areas (2025)

| Theme | 内容 | 現在の打ち手 |
|-------|------|-------------|
| Python Development | スクリプト / 自動化 / データ処理 | 効率的なコード最適化 |
| LLM Integration | AIモデル連携 / チャットボット / 分析 | OpenAI API / Hugging Face 実験 |
| Discord Bot | 多言語化 / 権限管理 / 分析 | Eventログ → 可観測性 |
| Next.js + API | ダッシュボード / Bot管理UI | App Router + Edge 実験 |
| Infrastructure | 自宅サーバー管理 / Proxmox VE / 仮想化 | VM・LXCコンテナ運用 / バックアップ・監視 / ネットワーク設定 |
| Automation | CI + 型検査 + Release | GitHub Actions 最適化 |
| Observability | レイテンシ計測 / ログ整形 | Structured Logging |
| Learning | Rust / Edge Functions | 小さなユースケース積み上げ |

---

## 🧪 Code Micro Samples

<details>
<summary><strong>Next.js (App Router) - Edge Ready API Route</strong></summary>

```ts
// app/api/health/route.ts
export const runtime = 'edge';

export async function GET() {
  return new Response(JSON.stringify({ status: 'ok', time: Date.now() }), {
    headers: { 'Content-Type': 'application/json' }
  });
}
```
</details>

<details>
<summary><strong>Discord.js Interaction Handler (Pattern)</strong></summary>

```ts
import { ChatInputCommandInteraction } from 'discord.js';

export async function handlePing(interaction: ChatInputCommandInteraction) {
  const started = performance.now();
  await interaction.reply({ content: '🏓 Pong!', ephemeral: true });
  const ms = performance.now() - started;
  console.log('[PING]', ms.toFixed(2), 'ms');
}
```
</details>

<details>
<summary><strong>FastAPI Minimal Service</strong></summary>

```python
from fastapi import FastAPI
app = FastAPI()

@app.get("/metrics")
def metrics():
    return {"uptime_sec": 1234, "version": "0.1.0"}
```
</details>

<details>
<summary><strong>Python LLM Integration (OpenAI)</strong></summary>

```python
import openai

def generate_response(prompt: str) -> str:
    response = openai.ChatCompletion.create(
        model="gpt-3.5-turbo",
        messages=[{"role": "user", "content": prompt}]
    )
    return response.choices[0].message.content

# Example usage
result = generate_response("Hello, how are you?")
print(result)
```
</details>

<details>
<summary><strong>Rails Controller Snippet</strong></summary>

```ruby
class HealthController < ApplicationController
  def index
    render json: { ok: true, time: Time.now.utc.iso8601 }
  end
end
```
</details>

---

## 🔄 Workflow Philosophy

```mermaid
flowchart LR
  Idea((Idea)) --> Scope[Scope Small]
  Scope --> MVP[MVP Build]
  MVP --> Measure[Metrics / Logs]
  Measure --> Iterate{Iterate}
  Iterate --> Automate[Automate Repetitive]
  Automate --> Scale[Scale / Refine]
  Scale --> Idea
```

- 余計な抽象化は後回し
- 計測できない改善は"感想"
- 先に価値を届けてフィードバック最速化

---

## 🤝 Work / Collab

| 提供できること | 例 |
|----------------|----|
| Python Development | スクリプト作成 / データ処理 / 自動化 |
| LLM Integration | AIチャットボット / テキスト生成 / API連携 |
| Discord Bot | 多機能管理 / 分析 / API連携 |
| Web / Dashboard | Next.js + API 統合UI |
| Infrastructure | 自宅サーバー構築 / Proxmox仮想化 / VM・LXC管理 / バックアップ・監視 |
| Automation | CI/CD・型チェック・Lint整備 |
| API連携 | Discord / OpenAI 等 |
| MVP構築 | 要件整理 → 最小実装 → 改善 |

> 小さなスパンでアウトプット → 進捗可視化を重視しています。

📬 連絡: **muzui122530@gmail.com**

---





## 🛠 Quick Scripts (Idea)

```bash
# update-all (例) : 依存を一括安全更新
for d in $(ls -d */); do
  (cd "$d" && [ -f package.json ] && npm update)
done
```

---
