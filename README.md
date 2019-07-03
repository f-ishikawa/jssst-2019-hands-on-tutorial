# jssst-2019-tutorial
**タイトル**

深層学習のテスト

**講師**

馬 雷（九州大学）
石川 冬樹（国立情報学研究所）

**日時**

2019年8月26日（月）

**注意事項**

本チュートリアルの大半は英語で行われます．必要に応じ質疑など日本語でフォローします．ハンズオンを行うためPCを持参して下さい．セットアップ等については後日掲載いたします．

**概要**

機械学習技術，特に深層学習技術の進化を受け，その産業応用に向けた取り組みが活発に行われています．すでに多くの実用化事例が出ているものの，機械学習を用いて構築した部品（ニューラルネットワーク等のモデル）やそれを含むシステム全体に関し，その構築や運用についての工学的な手法やノウハウは限られており，様々な問題提起や活発な議論が行われています．
機械学習工学研究会： https://sites.google.com/view/sig-mlse/
AIプロダクト品質保証コンソーシアム・2019年5月にガイドライン初版リリース： http://www.qa4ai.jp/
JSTによる戦略プロポーザル： https://www.jst.go.jp/crds/report/report01/CRDS-FY2018-SP-03.html

これに対しこの数年，ソフトウェア工学コミュニティからは第一歩として，機械学習モデルやそれを含むシステムに対するテスト技術の研究開発が盛んに行われてきました．ニューラルネットワーク等のモデルに対しては，テストに関する従来のアプローチが通じない場合が多々あります．例えば，様々な入力に対して期待する正解値を与えるのが高コストであったり不可能であったりします．またモデルは大きなブラックボックスであり，論理的に場合分け・分割して検査したり，テストの網羅性を考えたりするようなことは，少なくとも単純にはできません．これらの問題に対しては，入力の変化が出力にどう影響するかを考えるメタモルフィックテスティングや，ニューラルネットワーク内のニューロン発火パターンの多様性を評価するニューロンカバレッジなどの提案がなされています．

本チュートリアルでは，深層学習で構築された部品（モデル）に対するテスト技術に関する解説とハンズオンを行います．最新の論文で提案されているアプローチについて紹介するとともに，実際に手元で一定のテストを動かしてみます．これにより，参加者が深層学習モデルに対するテスト技術のねらいや意義について理解し，実活用に向けて議論したり今後の技術発展に追随したりすることができるようになることを目指します．
jst.go.jp
研究開発戦略センター（CRDS）は、国の科学技術イノベーション政策に関する調査、分析、提案を中立的な立場に立って行う組織として、平成15年（2003年）7月に、独立行政法人科学技術振興機構（当時の名称）に設置されました。
