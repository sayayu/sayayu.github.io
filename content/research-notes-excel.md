---
title: "Excel週次リサーチノート"
date: 2026-07-16
---

このページは、Excel・XLOOKUP・Excel関数・Excel業務効率化などのキーワードを軸に、週次で自動収集した注目記事・話題をまとめたリサーチノートです。

## 2026-07-16

### 1. Copilot in Excelに「マルチエージェントWeb検索」機能、2026年7月ロールアウトへ

- 概要: Microsoftは2026年7月、Copilot in Excelに複数のAIエージェントが協調して動作する新しいWeb検索機能を導入する。Conductor(統括)・Searcher(検索)・Verifier(検証)・Synthesizer(統合)・Auditor(監査)という役割の異なるサブエージェントが並行してリサーチを行い、各回答には出典の裏付け状況を示す「Trust Score」(信頼度バッジ)が表示される仕組み。
- 注目ポイント: 単なる機能追加ではなく、AIが生成した情報を複数ソースで相互検証し、根拠のない情報には「未検証」のフラグを立てるという設計思想が特徴。品質管理・データ検証の観点からも、生成AIの出力をどう「品質保証」するかという業界的関心と重なるテーマとして注目されている。
- 出典:
  - [Excel Copilot gains multi-agent web search with source citations in July 2026 | Windows News](https://windowsnews.ai/article/excel-copilot-gains-multi-agent-web-search-with-source-citations-in-july-2026.433269)
  - [Copilot in Excel is getting improved web search this month | Neowin](https://www.neowin.net/news/copilot-in-excel-is-getting-improved-web-search-this-month/)

### 2. Copilot in Excelでどのモデルを選ぶべきか ― Office Watchが実践ガイドを公開

- 概要: Office Watchが、Excel上のCopilotで選択可能になったAIモデル(GPT系、Claude Opus系など)の使い分けについて解説する記事を公開。長い数式チェーンの説明や矛盾点の洗い出しなど「深い推論」が必要な作業にはClaude Opus系、雑然とした指示からVBA/Office Scriptを組み立てるような作業にはGPT系が向くといった具体的な使い分けを紹介している。
- 注目ポイント: Excel Copilotのモデル選択肢が急速に増える中、「どれを選べば良いか分からない」という実務担当者の悩みに応える内容で、Microsoft 365利用企業のCopilot活用担当者を中心に関心を集めている。
- 出典:
  - [Best Copilot AI Model for Excel: A Plain English Guide | Office Watch](https://office-watch.com/2026/copilot-ai-model-for-excel/)

### 3. Microsoft 365ロードマップ2026年7月版 ― Copilot in Excelの「Skills」機能などを整理

- 概要: Level Up M365が、2026年7月分のMicrosoft 365ロードマップ更新をまとめた記事を公開。Copilot in Excelでは、繰り返し行う分析・モデリング・レポート作業を再利用可能な指示として登録できる「Skills」機能や、ワークブックごとにルールを定義できる「Workbook Rules」などが取り上げられている。
- 注目ポイント: 個々のニュース記事だけでは追いきれないロードマップ全体の動きを俯瞰できる内容で、IT管理者・情報システム部門の担当者が月次アップデートを把握する際の定番参照先として繰り返し引用されている。
- 出典:
  - [Microsoft 365 Roadmap Updates July 2026 | Level Up M365](https://levelupm365.com/2026/07/01/microsoft-365-roadmap-updates-july-2026/)

## 2026-07-19

### 1. Excelのメモリ情報漏えい脆弱性(CVE-2026-48580)、7月のPatch Tuesdayで修正

- 概要: 2026年7月14日のPatch Tuesdayで、Excelでワークブックを開いた際にメモリ上の内容が読み取られる可能性がある情報漏えい脆弱性CVE-2026-48580が修正された。Office 2016からMicrosoft 365 Appsまで広いバージョンが対象で、今月はExcel関連の修正パッチ数(34件)が例年より多いと報じられている。
- 注目ポイント: 「ファイルを開くだけ」で影響を受ける読み取り系の脆弱性という点、および今月のパッチがExcelに大きく偏っている点がセキュリティ専門メディアで話題になっている。業務でExcelファイルを日常的にやり取りするユーザーに向けて、即時のパッチ適用を呼びかける記事が相次いだ。
- 出典:
  - [Stop That Spreadsheet: Microsoft Fixes Excel's Memory Leak in July 2026 Update | Windows News](https://windowsnews.ai/article/stop-that-spreadsheet-microsoft-fixes-excels-memory-leak-in-july-2026-update.438657)
  - [July 2026 Patch Tuesday: 570 Fixes and a Critical BitLocker Flaw | Office Watch](https://office-watch.com/2026/july-2026-patch-tuesday/)
  - [CVE-2026-48580 - Security Update Guide | Microsoft MSRC](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-48580)

### 2. Excel世界大会の新企画「Landmark Battle」が街中で開催され、SNSで拡散

- 概要: Microsoft Excel World Championship(MEWC)とASUSが共催する新企画「Landmark Battle」が7月10日に開催され、自由の女神やエッフェル塔など世界の名所4か所から選手が同時に30分間・7段階のデータ課題に挑戦した。前王者アイルランドのDiarmuid Earlyが終盤の逆転で優勝し、The Registerなどが7月13日に取り上げた。
- 注目ポイント: スプレッドシート競技を屋外・観光名所という異例の舞台で開催した点が話題性を生み、選手入場や応援のクリップがTikTokやXで数十万〜100万回規模の再生数を記録するなど拡散した。業務ツールであるExcelがエンタメ・eスポーツ的コンテンツ化していく流れとして注目されている。
- 出典:
  - [Excel competition goes extreme, makes spreadsheet geeks compete from the street | The Register](https://www.theregister.com/offbeat/2026/07/13/excel-competition-goes-extreme-makes-spreadsheet-geeks-compete-from-the-street/5270709)
  - [World Excel Champion Diarmuid Early Stages Last-Minute Comeback to Win First Landmark Battle | ASUS Pressroom](https://press.asus.com/news/press-releases/asus-landmark-battle-diarmuid-early-wins/)

### 3. 週末に試したい、知られざるExcel機能5選(How-To Geek)

- 概要: How-To Geekが7月17〜19日の週末向けに、あまり知られていないExcelの便利機能5選を紹介する記事を公開。数式を一段階ずつ評価・可視化できる「Evaluate Formula」、Excel for the Web限定で入力例からその場で数式を自動生成する「Formula by Example」、選択範囲からグラフや条件付き書式などをその場でプレビューできる「Quick Analysis」などを取り上げている。
- 注目ポイント: 新機能紹介ではなく「既存だが埋もれている機能の再発掘」という切り口が実務層に刺さりやすく、週末読み物として拡散しやすい構成になっている。特に「Evaluate Formula」は数式デバッグ・レビューの観点で品質管理業務にも応用しやすい機能として目を引く。
- 出典:
  - [5 little-known Excel features to try this weekend (July 17-19) | How-To Geek](https://www.howtogeek.com/microsoft-excel-little-known-features-to-try-this-weekend-july-17-19/)

## 2026-07-26

### 1. xAIがExcel向け無料アドイン「Grok for Excel」を投入、Copilotに真っ向勝負

- 概要: 2026年7月20日、xAIがGrok 4.5を組み込んだExcel用アドイン「Grok for Excel」を公開した。Word・PowerPoint向けアドインも同時提供し、Microsoft Marketplaceからインストール可能。サイドバーから自然言語で数式作成・ピボットテーブル構築・データクレンジング・グラフ生成・Web検索結果の取り込みなどを指示でき、分析に使ったセルを明示する「根拠の可視化」が特徴とされる。
- 注目ポイント: Copilot in Excelと同じ土俵に競合AIが正面から乗り込んだ点が、「AIオフィス戦争」の新局面として海外メディアで大きく取り上げられた。The Registerが「なぜわざわざExcelのプラグインを作ったのか」と皮肉交じりに報じるなど話題性が高く、アドイン自体は無料でも実際の利用にはSuperGrok等の有料プランが必要な点も議論を呼んでいる。
- 出典:
  - [Grok muscles into Excel with an AI add-in of its own | The Register](https://www.theregister.com/ai-and-ml/2026/07/22/grok-muscles-into-excel-with-an-ai-add-in-of-its-own/5276138)
  - [Grok for Excel | xAI](https://x.ai/news/introducing-excel-addin)

### 2. MOS World Championship 2026がアナハイムで開幕、昨年準優勝の高校生の物語も再脚光

- 概要: 2026年7月26日から29日にかけて、Certiport主催の第24回Microsoft Office Specialist(MOS)World Championshipがカリフォルニア州アナハイムのディズニー・グランド・カリフォルニアン・ホテルで開催される。これに合わせ、2025年大会のExcel(Office 2019)部門で世界2位・賞金4,000ドルを獲得したシカゴ出身の高校生Xavier Diebold氏のサクセスストーリーを紹介する記事が公開された。
- 注目ポイント: 前週(2026-07-19分)で紹介した屋外イベント「Landmark Battle」に続き、Excel競技(スプレッドシート・エスポーツ)への注目がこの週も継続している。学生の等身大のサクセスストーリーは拡散しやすく、Excelスキルが賞金・進学など実利益に直結する事例として教育関係者からも関心を集めている。
- 出典:
  - [Excel Skills Earn Chicago Teen $4,000 at World Championship—Here's How to Build Your Own Office Proficiency | Windows News](https://windowsnews.ai/article/excel-skills-earn-chicago-teen-4000-at-world-championshipheres-how-to-build-your-own-office-proficie.440488)
  - [Excel World Championship: Xavier Diebold Takes Silver, $4,000 Prize | Windows Forum](https://windowsforum.com/windows-news.4/excel-world-championship-xavier-diebold-takes-silver-4-000-prize.440488/)

### 3. How-To Geekが週末企画「時短Excel Tips 5選(7/24-26)」を公開、地味な標準機能を再評価

- 概要: How-To Geekが7月24日、週末に試したい「時短につながるExcel機能5選」を紹介する記事を公開した。名前ボックスを使った高速ナビゲーション、「データの分析」によるピボットテーブル・グラフの自動提案、形式を選択して貼り付け(Ctrl+Shift+V)、「選択オプション」、「新しいウィンドウ」など、目立たないが実務で効く標準機能を取り上げている。
- 注目ポイント: 前週(7/17-19分)にも同シリーズで「知られざるExcel機能5選」を紹介しており、週末読み物の定番企画として定着しつつある。新機能紹介ではなく「既存機能の使い倒し」に焦点を当てる切り口は、業務効率化・時短をテーマにする読者層から継続的に支持されている。
- 出典:
  - [5 time-saving Excel tips to put to the test this weekend (July 24-26) | How-To Geek](https://www.howtogeek.com/microsoft-excel-time-saving-tips-to-try-this-weekend-july-24-26/)
  - [How-To Geek's Weekend Challenge: 5 Excel Tools That Could Save You Hours Every Week | Windows News](https://windowsnews.ai/article/how-to-geeks-weekend-challenge-5-excel-tools-that-could-save-you-hours-every-week.440442)
