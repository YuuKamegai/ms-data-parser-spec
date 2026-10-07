# ms-data-parser 仕様書

公開ページ: https://yuukamegai.github.io/ms-data-parser-spec/

MS-DIAL の出力を LLM から解析する MCP サーバ **ms-data-parser**（[systemsomicslab/Metabolomix_with_LLM](https://github.com/systemsomicslab/Metabolomix_with_LLM)）の仕様書です。
全 74 ツールの入出力、解析経路、前処理・PCA・差次的解析の計算、同定と MS/MS 照合、アラインメントのキュレーション（機械判別・注釈候補）、群別強度プロット、MS-DIAL Console と pipeline、エクスポート形式をまとめています。

- `index.html` は 1 ファイルで完結します（フォントのみ Google Fonts から読み込み）。
- 図中の「例示」と付いた数値・化合物名は説明用の架空の値です。
- 基準: Metabolomix_with_LLM `main@509f631`（2026-10-07）。
