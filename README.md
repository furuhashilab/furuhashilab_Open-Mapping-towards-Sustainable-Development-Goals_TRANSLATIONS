# Open Mapping towards Sustainable Development Goals — 日本語翻訳プロジェクト

**オープンマッピングとSDGsに関する書籍の日本語翻訳を整理・校正し、公開に向けて作業するプロジェクトです。**

青山学院大学・古橋研究室（[furuhashilab](https://github.com/furuhashilab)）で扱ってきた翻訳草稿を集約し、「どこまで訳されているか」「どの章に作業が残っているか」をGitHubで確認できるようにしています。

> **現在の進捗・残作業**  
> 📖 [章別の進捗台帳（translation-status.md）](translation-status.md) ｜ 🛠️ [Issues（未完了作業）](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues) ｜ 📝 [既存の和訳草稿13本（Issue #8）](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/8)

## 📚 翻訳対象

- **書名:** *Open Mapping towards Sustainable Development Goals*
- **編者:** Patricia Solís / Marcela Zeballos
- **出版:** Springer, 2023
- **原著・章別目次:** https://doi.org/10.1007/978-3-031-05182-1
- **原著のライセンス:** [Creative Commons Attribution 4.0 International（CC BY 4.0）](https://creativecommons.org/licenses/by/4.0/)

本書では、オープンな地図づくりや地理空間情報の活用が、持続可能な開発目標（SDGs）にどのように関わるかを扱っています。翻訳を通じて、日本語でも内容を参照しやすくすることを目指します。

## ✅ 翻訳の進捗

**2026年11月17日時点の進捗台帳に基づく状況です。** 「和訳本文あり」は翻訳・校正が完了したという意味ではありません。

| 区分 | 状況 | 参照先 |
| --- | --- | --- |
| 既存の和訳草稿 | 13本を収集・整理（第1〜33章のうち29章に和訳本文を確認） | [Issue #8](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/8) |
| 第21章の不足部分 | 追加草稿あり、原著との照合・校正待ち | [草稿](translations/chapter-21-sections-3-3.3.md) / [Issue #1](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/1) |
| 第23章の冒頭〜§3.3.3 | 追加草稿あり、原著との照合・校正待ち | [Issue #2](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/2) |
| 第27章・第28章 | 和訳本文が未確認、翻訳が必要 | [#3](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/3) / [#6](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/6) |
| 第32章・第33章 | 和訳本文が未確認、翻訳が必要 | [#5](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/5) / [#4](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/4) |
| 全体の校正・公開準備 | 原著照合、図表・出典・版差・公開可否などを確認 | [Issue #7](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/7) |

残る**新規翻訳は原著の約28ページ分**と見積もられています（進捗台帳の記載）。これとは別に既存訳の照合・校正が必要です。

最新の章別状況は [translation-status.md](translation-status.md) を確認してください。

## 🗂️ リポジトリの構成

```text
.
├── README.md
├── translation-status.md
├── LICENSE.md
├── Open Mapping towards Sustainable Development Goals.docx
└── translations/
    └── chapter-21-sections-3-3.3.md
```

- **README.md:** このプロジェクトの概要と参加方法
- **translation-status.md:** 既存原稿の収録範囲、章別進捗、残作業
- **LICENSE.md:** CC BY 4.0のライセンス本文
- **Open Mapping towards Sustainable Development Goals.docx:** リポジトリに置かれた作業用Wordファイル
- **translations/:** Markdown形式で管理する翻訳草稿
- **Issues:** 原稿の参照、翻訳・校正タスク、確認事項の管理

既存の和訳草稿13本は [Issue #8のコメント](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/8) に収録しています。**草稿があることと、内容の正確性・公開可否が確認済みであることは別**です。

## 🔧 作業の進め方

1. [進捗台帳](translation-status.md) を見て、担当する章と既存訳の有無を確認する。
2. [Issues](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues) から作業を選ぶ。既存のIssueがあれば、重複して作らずそのIssueを利用する。
3. [原著](https://doi.org/10.1007/978-3-031-05182-1) と照らし合わせ、章題・本文・図表・キャプション・参考文献を確認する。
4. 作成・修正した訳文をMarkdown等で記録する。章番号、対象節、原著ページ、出典を明記する。
5. 変更点と未確認箇所をIssueやPull Requestに記録し、レビューを受ける。
6. 確認が終わった内容を反映し、[進捗台帳](translation-status.md) を更新する。

### 翻訳・校正で確認したいこと

- **訳抜け:** 章・節・段落の抜け、原稿ファイルの境界で欠けた本文がないか
- **原著との一致:** 数値、固有名詞、専門用語、見出し、図表番号など
- **版差:** 既存草稿と参照している原著の内容が違わないか
- **文体:** 章内・章間で日本語の表現や用語が統一されているか
- **権利表示:** 著者名、出典、翻訳者、変更内容、ライセンスが明記されているか

作業途中でも、疑問点をIssueに残しておくと引き継ぎやすくなります。

## 📌 今後の作業

- [ ] 第27・28・32・33章の翻訳
- [ ] 第21・23章の追加草稿の校正・既存訳への接続
- [ ] 既存の和訳草稿13本と原著の対照
- [ ] 図表・キャプション・参考文献・章番号・版差の確認
- [ ] 寄稿者による翻訳原稿の公開可否確認
- [ ] 出典・クレジットを付した公開版の整備

個別タスクの詳細と作業状況は [Issues](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues) で管理します。

## 📄 出典・ライセンス・翻訳の取り扱い

原著は **CC BY 4.0** で公開されています。再利用・翻訳にあたっては、原著の著者・出典・ライセンスへのリンクを示し、翻訳などの変更を加えたことを明記してください。章ごとの著者と、第三者が権利を持つ図表等の扱いも確認が必要です。

既存の日本語訳については、**翻訳者・寄稿者の表記と公開可否の確認が完了するまで、公開可能な完成版とみなさない**方針です。確認事項は [Issue #7](https://github.com/furuhashilab/furuhashilab_Open-Mapping-towards-Sustainable-Development-Goals_TRANSLATIONS/issues/7) にまとめています。

- 原著: https://doi.org/10.1007/978-3-031-05182-1
- 原著ライセンス: https://creativecommons.org/licenses/by/4.0/
- リポジトリ内ライセンス本文: [LICENSE.md](LICENSE.md)

## 🤝 プロジェクト管理

管理: [furuhashilab](https://github.com/furuhashilab)（古橋研究室）

翻訳、原著照合、校正、進捗整理などの作業状況をGitHubに集約し、あとから参加する人にも経緯が分かる状態を目指します。質問や確認事項は関連するIssueへお願いします。
