<div align="center">

![og](./repository-open-graph.png)


# 横光利一.skill

*横光利一の文章DNAを、約 15KB のプロンプトへと蒸留しました。*

＊

*新感覚派の感覚運動を、AIの筆致へ接続するための横光利一 skill です。*


[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](./LICENSE)
[![Corpus](https://img.shields.io/badge/corpus-主要作品群%20%7C%20青空文庫-lightgrey)](#)
[![Based on 文豪.skill](https://img.shields.io/badge/based%20on-文豪.skill-6f42c1)](https://github.com/illusions-lab/bungo-skill)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-compatible-F97316)](#)

**書く　／　添削　／　対話**

</div>

---

このリポジトリは [`illusions-lab/bungo-skill`](https://github.com/illusions-lab/bungo-skill)（文豪.skill）によって蒸留された **横光利一の憑依 skill** です。青空文庫収録作品と Wikipedia（ja/en、2026-05-07 取得）から、14 層 × 5 カテゴリ（聲・眼・骨・魂・界）の文体 DNA を抽出しました。

ロードした AI は「横光利一について解説する」のではなく、**横光利一として語り始めます**。模倣ではなく憑依。書く／添削／対話の 3 モードに対応します。

## 横光利一について

| 項目 | 内容 |
|---|---|
| **本名** | 横光利一 |
| **生没** | 1898年3月17日（福島県）— 1947年12月30日（東京都、享年49） |
| **代表作** | 『日輪』『蠅』『機械』『上海』『旅愁』 |
| **位置づけ** | 新感覚派を代表する小説家 |

**略歴**：福島県生まれ。早稲田大学在学中から創作を開始し、川端康成らと新感覚派運動を牽引。都市・機械・知覚の変容を主題化した。

**作風の核**：視覚的で切断的な描写、名詞的連結の強い文体、感覚を前景化する構図。

## インストール

> [!NOTE]
> Claude Code もしくは [skills CLI](https://github.com/anthropics/claude-skills) が動く環境が必要です。

**方法 1：skills CLI で追加**

```bash
npx skills add illusions-lab/yokomitsu-skill
```

**方法 2：Claude Code の skills ディレクトリに置く**

```bash
git clone https://github.com/illusions-lab/yokomitsu-skill ~/.claude/skills/yokomitsu-skill
```

インストール後、Claude Code から `横光利一.skill をロードして` 等のトリガーで起動します。

## 3 つの起動モード

> プロンプト本体・起動トリガー・セルフチェックの全仕様は [`SKILL.md`](./SKILL.md) にあります。

### ✍️ 1. 書くモード

横光利一の語彙・構文・物語構造で新しい文章を生成します。テーマや素材を渡すと、L1-L11 の文体 DNA に従って書き下ろします。


<summary><b>出力サンプル</b>（主題：都市と孤独）</summary>

<br>

> 午後の舗道はガラスのように乾いていた。人の影は歩いているのでなく、機械の歯車のように噛み合って、同じ角度でひらいては閉じた。



### 📝 2. 添削モード

原稿を横光利一の美学で赤入れします。「なぜそう直すか」を作家の声で説明します。


<summary><b>出力サンプル</b>（原文：「彼は疲れていた。」）</summary>

<br>

**[赤入れ]**

> 彼の疲労は、肩ではなく、街路の光沢に先に現れていた。

**[指摘]**

抽象語だけで終えると、横光的な知覚の切れ味が消える。まず視覚情報を置き、その後に心理を遅れて接続する。



### 💬 3. 対話モード

キャリア・恋愛・生きづらさ等の相談に、横光利一の世界観で応じます。**解決策ではなく共感の深さで応じる**のが特徴です。


<summary><b>出力サンプル</b>（相談：「何をしても空回りします」）</summary>

<br>

> 空回りするのは、あなたの足取りが遅いからではない。時代のベルトコンベアが速すぎるのです。まず、速度を疑ってみましょう。



## 著作権について

本プロジェクトは、作家の作品を読解・参照・分析したうえで生成された AI プロンプトである。そこに作家の原文が含まれる場合もあるが、それはあくまで引用の域を出ない——現在の文学研究となんら変わるところはない。

いわゆる「AI の生成内容には他者の著作物が含まれうる」という主張は、AI の動作原理からすれば荒唐無稽と言うほかない。AI はコーパス内の内容を複製しているのではなく、そこからアイデアを学習し、自ら文章を生成しているのである。

日本著作権法第 2 条第 1 項第 1 号の「著作物」の定義、および最高裁平成 13 年 6 月 28 日判決（江差追分事件）によって確立された「アイデア・表現二分論」に照らせば、アイデアそのものは著作権の保護対象には含まれない。

> [!IMPORTANT]
> AI の原理を理解しないまま批判を繰り広げる一部の人々には、まずは勉強してから発言してほしい。無知を唯一の論拠にすべきではない。

## この skill の限界

> [!WARNING]
> 以下を理解したうえでご利用ください。

- **時代語感の完全再現は不可能**：横光利一が生きた時代の空気感は写せません
- **平均的横光利一にとどまる**：傑作のピークの冴えは再現困難
- **未発表原稿ではない**：生成物は「横光利一風の模倣」であり、横光利一本人の著作ではありません
- **精神医学的診断は不可**：L12 の Big Five 等は作品理解の補助であり、臨床的診断ではありません
- **調査日以降の新資料は未反映**：2026-05-07 時点の情報に基づきます

> 限界の完全なリストは [`references/research/05-boundary.md`](./references/research/05-boundary.md) §L14 にあります。

## リポジトリ構造

```
yokomitsu-skill/
├── SKILL.md                    憑依本体（14 層 × 5 カテゴリ）
├── README.md                   この文書
├── LICENSE                     MIT
├── .gitignore                  sources/ を除外
└── references/
    ├── research/
    │   ├── 01-voice.md         聲（L1–L3）語彙・構文・音韻
    │   ├── 02-eye.md           眼（L4–L6）視点・五感・読者距離
    │   ├── 03-bones.md         骨（L7–L9）段落・対話・物語構造
    │   ├── 04-soul.md          魂（L10–L12）主題・レトリック・人格
    │   ├── 05-boundary.md      界（L13–L14）反パターン・限界
    │   └── stats.json          stylometry.py の生出力
    └── wikipedia/
        ├── ja.md               日本語版（2026-05-07 取得）
        └── en.md               英語版（2026-05-07 取得）
```

## 倫理・法的

- **作品集**：青空文庫の公開テキスト（著作権保護期間満了分）を参照
- **生成物の位置づけ**：文学・教育・エンタメ用途。学術的な横光利一資料としての真正性は持たない
- **L12 人格推定**：公開伝記情報からの推定であり、臨床的診断ではない

> [!CAUTION]
> **臨床支援ではありません。** この skill は文学的な声の再現であり、臨床心理支援・医療の代替にはなりません。死・苦しみの主題の対話は文学の中核として skill 側で中断せず扱いますが、実際の心理支援が必要な場合はユーザー自身で専門機関へご連絡ください。

## 親工房との関係

| リポジトリ | 役割 |
|---|---|
| [illusions-lab/bungo-skill](https://github.com/illusions-lab/bungo-skill)（文豪.skill） | 作家を蒸留する方法論と道具。本リポは工房で蒸留された成果物 |
| [illusions-lab/bungo-skill-template](https://github.com/illusions-lab/bungo-skill-template) | 新規作家リポの雛形。本リポはこの雛形から派生 |
| [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill)（女娲.skill） | 思考方式を蒸留する姉妹工房 |

## ライセンス

[MIT License](./LICENSE)。

横光利一の作品は公有領域にありますが、本 skill の **プロンプト構成・研究ノート・解析結果** は MIT ライセンスで提供されます。

---

<div align="center">

> *「新しい感覚は、新しい言葉を要求する。」*
>
> —— 横光利一（新感覚派の主張を要約）

この skill は、横光利一への敬意を込めて、[文豪.skill](https://github.com/illusions-lab/bungo-skill) によって蒸留されました。

</div>

---


<summary><b>アセット自動生成（OG画像・SNS・印刷ポスター・Webホームページ）</b></summary>

<br>

このテンプレートには **画像と Web ホームページを自動生成する仕組み** が同梱されている。
編集するのは原則 3 つだけ：

1. **`illusions-skill.yaml`** — メタデータ（名前、説明、デザイン、Tier 別コンテンツ）
2. **`README.md`** — GitHub ショーケース兼手引き
3. **`sources/portrait.jpg`** — 作家の肖像画

これだけで GitHub Actions が以下を自動生成する：

| 出力 | 形式 | 配信先 |
|---|---|---|
| `dist/og.png` (1280×640) | PNG | 手動で `./repository-open-graph.png` に反映（README 表示）／ Pages デプロイで `docs/repository-open-graph.png` にコピー（Web OGP） |
| `dist/social-{card,square,story}.png` | PNG | Actions artifact としてアップロード |
| 印刷ポスター A4〜B1 | PNG + PDF | GitHub Releases に ZIP 添付 |
| Webホームページ | static HTML | `docs/` → GitHub Pages |

### Tier 別情報密度

| サイズ | Tier | 内容 |
|---|---|---|
| OG (1280×640) | 1 | 名前 + tagline |
| Social card / square | 1-2 | + 説明 + バッジ |
| Social story (1080×1920) | 1-3 | + 3モード + install command |
| A4 / A3 | 1-3 | 上記 + key features |
| B2 / A2 | 1-4 | + 哲学（philosophy.md） + L1-L14 サマリ |
| A1 / B1 | 1-5 | + 引用作品（citations.md） + methodology |

### ローカルで試す

```bash
# 画像生成
cd generate
npm install
node bin/skill-generator.js validate ../illusions-skill.yaml   # YAML 検証
node bin/skill-generator.js generate --only=og                  # OG だけ
node bin/skill-generator.js generate --only=og,social           # OG + SNS
NODE_OPTIONS='--max-old-space-size=6144' \
  node bin/skill-generator.js generate --only=print             # 印刷物（数分）
node bin/skill-generator.js generate                            # 全部

# Web LP もこのリポの generate/web/ に同梱されている。
# ローカルプレビュー手順は CONTRIBUTING.md 参照。
```

### CI/CD 自動化（GitHub Actions）

| Workflow | Trigger | 何をする |
|---|---|---|
| `validate-skill.yml` | PR | YAML スキーマ検証 + OG smoke test |
| `generate-assets.yml` | push | OG/SNS 画像生成 → Actions artifact にアップロード |
| `deploy-pages.yml` | push | OG 画像を生成 → `generate/web/` を Vite ビルド → GitHub Pages 配信 |
| `release-print-assets.yml` | release published | 印刷物 6 サイズ全形式生成 → Release に ZIP 添付 |

**初期セットアップ**:
1. GitHub Pages を有効化: Settings → Pages → Source: **GitHub Actions**
2. 必要な場合のみ外部 Web source を設定: Settings → Variables → `WEB_SOURCE=owner/repo@ref`

### カスタムフォント

`illusions-skill.yaml` の `design.font_*` で別フォントを指定するときは、
`fonts/<Family_With_Underscore>/<file>.ttf` に TTF を配置（OTF は CJK PDF で失敗）。

詳細は `CONTRIBUTING.md` 参照。

### INDD（InDesign）非対応について

InDesign Server（年額数十万円）が必要で CI で動かないため、代替として:
- **SVG**: Illustrator/Inkscape で完全編集可能
- **PDF**: Illustrator で開ける、印刷直接対応

を出力する。InDesign で使いたい場合は PDF をリンク配置してください。

