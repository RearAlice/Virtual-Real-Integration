# Virtual-Real-Integration【仮想・現実統合】
[![English README](https://badgen.net/badge/README/in%20English/blue?icon=github)](/README.md)

このリポジトリは、現実世界と仮想世界の統合に関する[ユースケース](https://github.com/MetaverseStandards/Virtual-Real-Integration/blob/main/src/readme.md)（UC）を探求するためのものです。

最初のユースケース（UC1）、[Assisted Car-Human Urban Rendezvous（支援付き都市部での車と人の待ち合わせ）](https://github.com/MetaverseStandards/Virtual-Real-Integration/blob/main/src/UC1/readme.md)は、私たちが会議で断続的に話し合ってきた「乗客をピックアップするために到着するライドシェア」というシナリオの一般的なアイデアに基づいています。

2番目のユースケース（UC2）、[Underground Utilities - Reading the Street（地下埋設物 - 道路の読み取り）](https://github.com/MetaverseStandards/Virtual-Real-Integration/tree/main/src/UC2)は、建設現場での掘削前および掘削中に、損傷や事故を防ぐために地中に何が埋まっているかを理解する必要性に基づいています。埋設された配管やケーブルの位置は、設計と掘削が進むにつれて、さまざまな精度レベルでしかわからないことがよくあります。
1.  **設計段階**では、埋設された配管やケーブルに関する一般的な記録はあるものの、それは広い範囲内に存在するという情報だけであったり、あるいは地下面の統合ビューを提供するために使用できる「竣工時の」ビデオや画像があったりします。
2.  **位置特定段階**では、水平方向の精度は数十センチメートル、垂直方向の精度は半メートル程度まで向上する可能性があります。
3.  **掘削段階**では、掘削エリア内で正確な位置と状態が露出します。

統合された仮想/現実ビューは、作業の進行に合わせて更新でき、常に最新で最良の情報を提供します。当初は隠れていた埋設物の情報が、直接の観察によって非常に大まかなものから正確なものに置き換えられるため、これらの「竣工時の」観察に基づいてモデルを更新することが可能です。これにより、将来別のプロジェクトが同じ埋設物を扱う場合に、その情報を統合ビューに組み込むことができます。

***

## 計画

1.  **EG議長**: UC1の初期バージョンを提供し、プロセスを開始します。これに着手するため、私（スティーブ）は、最初の6回の会議の一部をリバースエンジニアリングし、[James Jackson氏のビルディングブロック](https://github.com/MetaverseStandards/Virtual-Real-Integration/tree/main/src/buildingblocks#readme)（BB）を含む、UC1の完全かつ内部的に一貫性のあるバージョンを作成しています。これには、UC1のより詳細な物理的および意味的要素クラス（SEC）が含まれます。後者は、James Jackson氏のスライドにあった「Reality Players」に相当します。私たちは、UC1のみを対象とした「ユースケースワールド」（UCW）の、ほぼ**完全**で内部的に一貫性のある意味的要素クラス（SEC）の初期セットから共同作業を開始できます。

2.  **共同作業**: James Jackson氏のビルディングブロック（BB）とSECにサービスインターフェース（SI）を追加し、SECのインスタンスがUC1を実行できるようにします。

3.  **共同作業**: UC1のグラフを発展させ、UC1のコンセンサス構造に到達します。ここでは、意味的クラスやインターフェース（つまり、すべて）を変更することができます。

4.  **全体での決定**: 合意形成されたUC1グラフを、ワーキンググループの基盤として採用するかどうかを決定します。このワーキンググループは、技術的に実現可能なメタバースにおける現実/仮想世界の統合を実装するために、既存の標準とそれを補完する追加の標準の利用可能性を実証するUC1のプロトタイプを開発することを目指します。

***

## 次のステップ

上記の計画とUC1の選択の両方について、皆さんのニーズ、意見、アイデアを反映したIssueを立ててください。

ユースケース1に関して、データが投入された統合ワールドの例の[ビルディングブロック](https://github.com/MetaverseStandards/Virtual-Real-Integration/tree/main/src/buildingblocks#readme)、[基本スキーマ](https://github.com/MetaverseStandards/Virtual-Real-Integration/tree/main/src/UC1/world)、[ユースケース記述](https://github.com/MetaverseStandards/Virtual-Real-Integration/tree/main/src/UC1#readme)、[アクションシーケンス](https://github.com/MetaverseStandards/Virtual-Real-Integration/tree/main/src/UC1/sequence#readme)、そして[マークダウンマニフェスト](https://github.com/MetaverseStandards/Virtual-Real-Integration/blob/main/src/UC1/world/integrated/integrated.md)が準備できています。